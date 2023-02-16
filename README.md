# Introduction
Distracted drivers contribute to more than 3000 road accidents per year, which unfortunately led to 93 deaths in 2018. This report details the steps taken to develop a machine learning model to identify photographs of distracted driving behaviours. 

# Objective
Given a Kaggle competition dataset of 2D dashboard camera images (https://www.kaggle.com/c/state-farm-distracted-driver-detection/overview) containing both safe and unsafe behaviours, a convolutional neural network (CCN) was developed to classify each driver's behaviour and determine if they are driving attentively, wearing their seatbelt etc. or if they were engaging in unsafe, distracted behaviours that may result in injury, or even death. 

# Method
A deep-learning algorithm was developed using Python. The driver images were downloaded and pre-processed and a training model was built to classify a training set of driver images. The model was then tested and improved, and used to classify a test set of images. 

# Results
The final model converges quickly and does not show a significant amount of underfitting or overfitting, indicating that the model is accurate (fig 1). The confusion matrix in fig 2 shows high level of accuracy across all categories, however when applying the model to the test set, some problematic classes were identified (i.e. where the drivers actions were less clear). 
 
Figure 1 - Training vs Validation
 
Figure 2 - Confusion Matrix
Novelty
This report demonstrates a novel approach in comparison to previous publications (particularly ones that utilise the same competition dataset) by identifying training parameters there were inappropriate and adjusting those following analysis of the initial results to get a substantially more accurate model. 



# Distracted Driver File Guide

Dependencies.txt - List of all dependencies required to run the code

CSC8635 University Assignment - S.Knox C1000466.html & .IPYNB - Final report that contains 
explainations of investigations carried out and all code to run the model. 

Structured Abstract - Explains the key aspects of the project and summarises the outcome with Key Images.  

Output File Examples - As the output files were too large to upload to Ness, a small sample were included in this folder.





Dataset - The kaggle dataset that was used for this project can be found here: 
https://www.kaggle.com/c/state-farm-distracted-driver-detection/overview

GIT - All files are saved in the following Githib location: 
https://github.com/Knoxyherself/Machine-Learning-Module


