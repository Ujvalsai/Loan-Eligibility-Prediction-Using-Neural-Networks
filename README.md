# Loan_Eligibility_Prediction_v2

The main goal of this project is to predict if a customer is eligible for loan sanction based on
the give data.
Initial we take a vast quantity of data set to predict the outputs.
Here we will be using Neural Network Algorithm which is implemented by using the
Tensorflow.

# Why Neural Networks ?

As we all know, predictive analytics combines techniques like predictive modeling with
machine learning to analyze past data in order to predict future trends.
But neural networks differ from regular predictive tools. The most-oft used model - linear
regression - is actually a very simple way of going about things as compared to a neural
network.
Neural networks work better at predictive analytics because of the hidden layers. Linear
regression models use only input and output nodes to make predictions. Neural network also
use the hidden layer to make predictions more accurate. That’s because it ‘learns’ the way a
human does.

## Implemetation

The implementation has 8 parts in it.,
  1. Dataset selection
  2. Identifying the libraries
  3. Preprocessing the data
  4. Splitting the data
     i. Training
     ii. Testing
     iii. Evaluation
  5. Setting up the Neural Architecture
  6. Deciding the working parameters
  7. Fitting the data and adding weights
  8. Visualizing the Accuracy and Loss

# Data Selection

* We got the datasets from a github profile
* LINK : https://github.com/shrikant-temburwar/Loan-Prediction-Dataset
* There are 12 columns which we use for inputs
* The 13th column is the loan approval status

# Architecture

* We will be using a 4 step multilayer
* Feedforward network
* The input layer is of size 11
* There are two hidden layers each of size 32
* Finally there a output layer of size 1
![Model](https://github.com/Ujvalsai/Loan_Eligibility_Prediction_v2/blob/main/Model.PNG)
