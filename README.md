# Pix2Pix_CFD
An AI model to depict fluid flow.

# About Project
Inspired by https://github.com/loliverhennigh/Steady-State-Flow-With-Neural-Nets , this is a re-implementation on a keras framework with an U-net architecture for the AI model. The training data is borrowed from the shared repository to validate the implementation.

The model tries to predict the velocity magnitude over different shapes of car.

# Training data
training data is available here: https://drive.google.com/file/d/0BzsbU65NgrSuZDBMOW93OWpsMHM/view?usp=sharing (about 700 MB). Place this file in the directory and edit the notebook accordingly.
Testing data can be found here : https://drive.google.com/file/d/0BzsbU65NgrSuR2NRRjBRMDVHaDQ/view?usp=sharing

# Ideas for future work
1) Predict the drag intensity.
2) Predict the mesh size for LES simulation using RANS results as training data.
