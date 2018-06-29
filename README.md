# Bank-Note-Authentication-Artificial-Neural-Network-Tensorflow-Model-Gradient-Descent-Optimizer

An Artificial Neural Network Model using Tensorflow and Gradient Descent Optimizer, it can identify whether a note is a real note or a fake one.

### Data Set Information:
https://archive.ics.uci.edu/ml/datasets/banknote+authentication
Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

### Attribute Information:
1. variance of Wavelet Transformed image (continuous) 
2. skewness of Wavelet Transformed image (continuous) 
3. curtosis of Wavelet Transformed image (continuous) 
4. entropy of image (continuous) 
5. class (integer) 

Using Tensorflow created a deep neural network or artificial neural network for creating and saving the model(checkpoint). The python code file "NotesAuthentication.py" contains comments that are easy to understand what every function does. Uses one hot encoding for the labeled output of the dataset.

I have created a multilayer perceptron with 4 hidden layer and 10 neurons each layer that uses gradient descent optimizer to minimize the cost with 200 epochs.

The output or the accuracy is as given below.
