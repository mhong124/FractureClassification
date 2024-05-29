# FractureClassification

## About Our Project

In our project, we learned how to utilize a sequential neural network model to predict whether X-Ray images of bones were fractured or not fractured. To do this given a training, testing, and validation set of labeled images (fractured or not fractured), we processed images in given directories of images to extract their labels and to load images with resizing and reshaping to ultimately access image arrays. We created a function to complete image processing and ran it on our test train and validation paths to extract their labels and image arrays. 

We then prepared the model, in which we used a sequential neural network model with customized layers. For our model's layers, we generally followed a convolution 2D layer into normalization into dropout layer in order to prevent overfitting. Additionally, we utilized max pooling in order to process our data through our neural network. We finished off the initialization of the layers of our model by filtering through layers of dense layers in order to apply activiation functions (ReLU and sigmoid). 

We then compiled our model and fit it to our training and validation data. We processed this with 20 epochs to analyze each epochs loss and accuracy. To visualize these findings we graphed the train and validation accuracy against eachother by progression of epochs. We also graphed train and validation loss in a similar way against each other by epochs. To further analyze our results, we predicted with test data and foudn accuracy, precision, recall, and F1 score. To finalize our findings, we visually displayed a confusion matrix based on predicted labels we had found and their accuracy, precision, and recall.  

### Built with

- pandas
- numpy
- os
- tensorflow
- keras
- seaborn
- matplotlib.pyplot
- PIL.Image

