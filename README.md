# Handwritten-Digit-Recognition-
A Convolution Neural Network is built to classify MNIST  Handwritten Digit Recognition.Here digit recognition is implemented using tensorflow and pytorch 


In this tutorial, we'll build a TensorFlow and Pytorch model to recognize handwritten digits with a convolutional neural network. First, we'll train the classifier by having it "look" at thousands of handwritten digit images from the MNIST handwritten digit dataset and their labels. Then we'll evaluate the classifier's accuracy using test data that the model has never seen.

This task is considered a classification task as we are training the model to assign a category (the digit that appears in the image) to the input image. We will train the model by showing it many examples of inputs along with the correct output. This is referred to as supervised learning.

##What you will build

You will make a webpage that uses TensorFlow.js to train a model in the browser. Given a black and white image of a particular size it will classify which digit appears in the image. The steps involved are:

Load the data.
Define the architecture of the model.
Train the model and monitor its performance as it trains.
Evaluate the trained model by making some predictions.
