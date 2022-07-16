# ANN
ML

In this homework, you will apply what we learned to a classic handwritten digit classification 
problem. The inputs are images containing handwritten digits from 0 to 9. The output of the 
classification should the correct label (0-9).


## Data availability:
http://amlbook.com/support.html
Please scroll down to the bottom of the above page to download the data. You can get both the 
extracted features (symmetry and intensity) and also the raw features. When we use “two 
features”, we refer to the extracted features. If we use “raw features”, we refer to the 256 
grayscale values.

(My train and test data all came from the above link.)

## description
Apply neural network of 1 hidden layer to classify 1 and 5. The features are: 
symmetry and average intensity. Use 3-fold cross-validation. Clearly describe and/or
plot your network structure, such as the number of units in each layer. Train/test at 
least 3 sets of different number of hidden units. Compare their performance: in-sample 
error and test set error. 

3-fold cross validation: divide your data into three parts, use 2 parts for training and the 
third part for testing.
