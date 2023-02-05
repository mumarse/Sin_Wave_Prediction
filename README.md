#Sine Wave Prediction using RNN and LSTM
This project is a demonstration of predicting sine wave using Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) in Python using TensorFlow.

##Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
The following packages are required to run this project:

TensorFlow
Numpy
Matplotlib
You can install these packages using the following command:

pip install tensorflow numpy matplotlib
Running the Code
To run the code, clone the repository and run the following command:

python sine_wave_prediction.py
Project Overview
The project consists of two main parts:

Generation of sine wave data
Model training and prediction
The sine wave data is generated using Numpy's linspace function and the sine function. This data is then divided into training and testing sets.

The model training is done using TensorFlow's Sequential API. An LSTM layer is added to the model followed by a fully connected dense layer to make predictions. The model is then trained using the training data.

Finally, the trained model is used to make predictions on the test data and the results are visualized using Matplotlib.

Conclusion
This project demonstrates the use of RNN and LSTM in predicting sine wave. The results show that LSTM provides better predictions compared to RNN. This project can be used as a starting point for further exploration in the field of time series prediction.



