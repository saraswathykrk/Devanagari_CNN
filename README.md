## Classification of Hand-written images of Devanagari Script

Please open the jupyter notebook to see the entire code. This code is used to classify hand-written images of Devanagari script using tensorflow and CNN.

The Devanagari character set consists of 46 characters - 36 alphabets and 10 numbers. Here we will first pre-process the images and then train a neural network(convolutional neural network) on the training samples. Once done, we will divide the train  dataset into training and validation set and then perform the training. At the end, we will use the test set and make predictions and plot a few graphs to see how well our model is performing. We will use tensorflow Apis for training the CNN and matplotlib library for plotting the graphs.

Ensure all the required libraries are installed before running the jupyter notebook.

###     Contents
#####     1. Get the Data
#####     2. Plotting the data - For understanding the dataset
#####     3. Tensorflow Functions for CNN - Model Architecture and construction, using different TF APIs.
#####     4. Training the model (how to feed and evaluate Tensorflow graph)
#####     5. Prediction
