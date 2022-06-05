# Neural_Network_Charity_Analysis

## Overview of the Analysis

The pupose of this analysis was to apply all learned in module 19 Neural Networks amd Deep Learning Models, to execute it was used Google Colab, TensorFlow platforom (Python), to review, analize and classify the suceess of donations in a data set named charity_data.csv. It was used in the execution of two analysis "AlphaSoupCharity.ipynb" and "AlphaSoupCharity_Optimization.ipynb" the following methods for the challenge execution:
* Proprocesing the data for the neural network model compile
* Train and evaluate the model
* Optimize the model
* The results were saved to two HDF5 files "AlphabetSoupCharity.h5" and "AlphabetSoupCharity_optimized.h5"

All was properly executed comply with the challenge deliverables indicated below:

## Deliverables:

This challenge 19 consisted in four deliverables as indicated as followows:

* Deliverable 1: Preprocessing Data for a Neural Network Model
* Deliverable 2: Compile, Train, and Evaluate the Model
* Deliverable 3: Optimize the Model
* Deliverable 4: A Written Report on the Analysis README.md

The results will be detailed in the following section.

## Results
Data Preprocessing
Developing this analysis and model, the target was held in IS_SUCCESSFUL field.

The variable(s) detailed as follows, should be considered on features model
* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE

The variable(s) detailed as follows were removed from input and data.
* NAME
* EIN
* Compiling, Training, and Evaluating the Model

Model Configuration:

* hidden_nodes_layer1 = 80
* hidden_nodes_layer2 = 30
* number_input_features = 43

Pleasee code below and results below

![this is an image](https://github.com/JJF1962/Neural_Network_Charity_Analysis/blob/main/Images/Capture.PNG)

This model acheived initially 73.24% accuracy as you can see below


![this is an image](https://github.com/JJF1962/Neural_Network_Charity_Analysis/blob/main/Images/Capture%20fig%202.PNG)


Later in the alphabetSoupCharity_Optimization notebook, it were executed 3 attempts tto incraese the accuracy, using codes to increase the number of hidden nodes in layer 1 (3 X number of input features),  the number of hidden layers to include a 3rd
changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer as you can see reults in the figure below:

![this is an image](https://github.com/JJF1962/Neural_Network_Charity_Analysis/blob/main/Images/Capture%20fig%203PNG.PNG)


Additionally it was  saved to files "AlphabetSoupCharity.h5" & "AlphabetSupCharity-optimized.h5" in Google Colab and uploaded to the Github repository as well


## Summary
After the execution of the three delliverables The deep learning neural network model no allow me to reach the target accuracy of 75%. and the final result was lower that the first one obtained before obtimze.based on it it is is posible to consider that this target level is pretty low,  not be consider an outperform. 
