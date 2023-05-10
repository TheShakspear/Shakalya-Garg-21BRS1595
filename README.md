# Handwritten Digit Recognition

So I have been learning the concepts related to neural networks recently, and hence thought of making basic projects related to it.
One such example that caught my eye was handwriting detection. Hence I have created a basic neural network model using the Sequential 
model with Flatten and Dense as layers. The training and testing data for the model has been taken from mnist which basically contains
different handwritten digits with a pixel size of 28x28. This dataset is already divided in training and testing.

## Training Model
Sequential model is taken into account with four such layers, the first one being Flatten which is used to convert the 2d image pixels into a 1d vector.
Next two layers are Dense layers with 128 units or neurons each using 'relu' or Rectified Linear Activation Function and finally the fourth or the last 
layer using 'softmax' with 10 units or neurons. This basically acts on probablities and returns the most probable answer that the digit might be.

## Testing Model
The model when tested using the test_dataset of mnist, resulted in an accuracy of around 97.2% with a loss of 9.2%, although when datasets made by me were fed
the model behaved poorly. So currently I am trying to rectify the same.
