## A Data-Driven Analysis of Spatiotemporal Cues and Experience Accumulation Effects for Pitch Type Prediction
# Overview
This repository provides the implementation of the machine learning (ML) analysis presented in the paper titled "A Data-Driven Analysis of Spatiotemporal Cues and Experience Accumulation Effects for Pitch Type Prediction." Our analysis identifies spatiotemporal cues for prediction and quantifies the effect of accumulating opponent-specific information across trials, given that predictive cues embedded within movements can enhance the prediction accuracy of ML model. 

# Repository Structure
pitch_type_pred/  
├── dataset &nbsp;&nbsp;&nbsp; # The datasets of the eight baseball pitchers(sub01-08)  
├── program &nbsp;&nbsp;&nbsp; # Program codes for the proposed analysis  
└── results &nbsp;&nbsp;&nbsp; # The results of the proposed analysis  
└── README.md &nbsp;&nbsp;&nbsp; # This file  

# Installation
This project is designed to be easily executed in Google Colab.
All experiments and demonstrations can be reproduced by mounting the project folder and running the main notebook.
First, open a new Google Colab notebook and make sure that the runtime type is set to GPU
(Runtime → Change runtime type → Hardware accelerator → GPU).
Then, mount the project directory named "pitch_type_pred."
If you store this folder on your Google Drive, the following step will make it accessible inside Colab.
Once the folder is mounted, navigate to the project path and execute the main notebook to start the program ("main_program.ipynb").

# Requirements
・Google Colab (Python environment)  

# Citation
・Coming soon
