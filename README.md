# stock prediction
 
Stock Price Prediction using Machine Learning is the practice of forecasting the future value 
of a stock traded on a stock exchange in order to benefit from it. The dataset can be 
obtained from https://finance.yahoo.com/

The libraries like matplotlib, pandas, numpy are used in this project. Furthermore, 
normalization and rescaling of data is done. To create the LSTM, I need to import a few 
Keras functions: sequential to initialise the neural network, LSTM to add the LSTM layer, and 
LSTM to add the LSTM layer. Dropout is used to prevent overfitting by using dropout layers, 
while Dense is used to add a densely linked neural network layer. After completing all of 
these procedures, I can use matplotlib to show the difference between the predicted and 
real stock prices. The approximate accuracy of the model is 91%.

The model is typically trained on historical stock prices and other relevant features, such as 
technical indicators and economic news, to learn the patterns and trends in the data. The 
trained model can then be used to predict future stock prices based on new input data.

References:

https://www.youtube.com/watch?v=hpfQE0bTeA4
https://www.kdnuggets.com/2018/11/keras-long-short-term-memory-lstm-model-predictstock-prices.htm