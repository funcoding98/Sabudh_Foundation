LAB_8

Classification - IBM HR Analytics Employee Attrition & Performance
Objective: Build models using all classification algorithms other than neural networks and and compare the accuracy using methods discussed with them
Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’ (It's up to you to explore and find patterns in the dataset by asking questions of your choice). Finally, predict the “Attrition” from this data set.

Assignment Guidelines:
Do basic analysis and Visualization of all the columns and select the columns which you feel are relevant for solving the problem statement. (Don’t forget to preprocess your data)
Explore different scoring metrics (like F1 score, accuracy, precision, etc.) and select the most relevant.
Experiment with different classification algorithms and Don’t forget to perform hyperparameter tuning on these models
Make sure to provide import features for at least one of the models 5. Finally in conclusion section make sure to compare all your models

LAB 9

Implementation of the backpropagation algorithm for training a neural network on mnist data
For this coursework you are required to write your own implementation of the backpropagation algorithm for training a neural network. You are required to do this assignment in the Python (Python version 3) programming language. Do not use any audodiff toolboxes (TensorFlow, Keras, PyTorch, etc) - you are allowed to use only numpy like libraries (numpy, pandas, etc). 

The goal of this assignment is to label images of 10 handwritten digits of “zero”, “one”,...,“nine”. The images are 28 by 28 in size (MNIST dataset), which we will be represented as a vector x of dimension 784 by listing all the pixel values in raster scan order. The labels are 0,1,2,...,9 corresponding to 10 classes as written in the image. There are 3000 training cases, containing 300 examples of each of 10 classes.

LAB_10

Problem Statement 1 : Say you are standing at the bottom of a staircase with a dice. With each throw of the dice you either move down one step (if you get a 1 or 2 on the dice) or move up one step (if you get a 3, 4 or 5 on the dice). If you throw a 6 on the dice, you throw the dice again and move up the staircase by the number you get on that second throw. Note if you are on the base of the staircase you cannot move down! What is the probability that you will reach more than 60 steps after 250 throws of the dice. Change the code so that you have a function that takes as parameter, the number of throws Add a new parameter to the function that takes a probability distribution over all outcomes from a dice throw. For example (0.2,0.3,0.2,0.1,0.1,0.1) would suggest that the probability of getting a 1 is 0.2, 2 is 0.3 etc. How does that change the probability of reaching a step higher than 60?

Problem Statement 2 : . Generate random data for for Multiple Linear Regression, Logistic Regression, K-mean Clustering

Problem Statement 3 : Implement the following algorithms from scratch using numpy only and using the data from Question 2 “for loop” 
                      a. Linear Regression using Gradient Descent 
                      b. Logistic Regression using Gradient Descent 
                      c. Linear Regression with L1 and L2 Regularization 
                      d. Logistic Regression with L1 and L2 Regularization 
                      e. K-Means

Problem Statement 4 : Change code into an Object Oriented Project reusing part of the code where possible
