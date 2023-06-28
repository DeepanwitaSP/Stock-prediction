# Stock-prediction

This project utilizes LSTM (Long Short-Term Memory) recurrent neural networks to predict stock prices.
It trains on historical stock price data and generates predictions for future stock prices.
The google stock price data set which is available in the repository is used to train the model.

## Data preprocessing:

Before training the model, some data preprocessing steps are performed:
To fit the data to the RNN model the shapes of X & Y must be same. So we used feature scaling method to normalize the data.


## Libraries used

numpy: For mathematical computing in Python.
pandas: For data manipulation and analysis.
matplotlib.pyplot: library for creating visualizations.
seaborn: A statistical data visualization library based on matplotlib.
sklearn.model_selection: A module in scikit-learn for model selection and evaluation.
sklearn.preprocessing: A module in scikit-learn for data preprocessing tasks.
keras: Keras is a high-level deep learning library used for implementing recurrent neural networks.

## Conclusion

The predictions are based on the trained LSTM model. You can give a different data set of stock prices and the model 
will try to predict the stock price. The program will display a graph comparing the real stock prices and the predicted stock prices.
