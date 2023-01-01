# Neural Network Modelling in Python: Predicting Applicant Success for Alphabet Soup

## Overview of Project

### Purpose

The purpose of this project is to use machine learning and neural networks for a dataset to create a binary classifier that can then be used to predict whether or not applicants would successful in obtaining funding from Alphabet Soup. The dataset includes EIN, name, application type, application, classification, use case, organization type, status, income amount, special consideration, ask amount, and if it was successful.

## Results

* The variable that is the target of the model is whether or not the application was successful
* The variables that are the features of the model are application type, application, classification, use case, organization type, status, income amount, special consideration, and ask amount.
* The variables that are dropped are EIN and name.
* Initially, I selected two hidden layers. The first had 75 and the second had 40, the activation function for the hidden layers are relu and for the output layer was sigmoid. Then, to optimize, I increased the number of hidden layers to 3, I increased the neurons to 150 for the first layer, 135 for the second layer, and the third layer had 110 which should increase the pace of the model. I also reduced the number of epochs to optimize from 100 to 35 given that the loss was no longer significantly decreasing after 15.
* I was not able to achieve the target model performance
* The steps I took to increase performance were reduction of epochs, increase neurons, and increasing the number of hidden layers.

## Summary

The performance achieved is 60%. Possibly removing certain variables such as application type which may be unnecessary noise could be conducive to improving the accuracy of the model.
