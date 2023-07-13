# Stock_Pice_Predition

 This code will first load the stock price data for Microsoft from a CSV file. Then, it will scale the data so that it is between 0 and 1. The data is then split into train and test sets, with 80% of the data used for training and 20% used for testing.

 The LSTM model is then created with 50 neurons in the hidden layer. The model is then compiled using the mean squared error (MSE) loss function and the Adam stochastic gradient descent optimizer. The model is then trained for 100 epochs.

 Finally, the model is used to make predictions for the test data. The predictions are then plotted along with the actual stock price data.

# Getting Started

To run this code, you will need to have the following Python libraries installed:
```bash

NumPy
pandas
matplotlib
Keras
Sklearn
```



You can also run this code on Google Colab, which is a free online Jupyter Notebook environment.
