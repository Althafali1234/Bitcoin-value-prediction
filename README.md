Bitcoin price analysis and prediction project using historical BTC-USD data and an LSTM model to analyse price trends and predict future Bitcoin prices.
# Bitcoin Price Prediction Using LSTM

## About the Project

This project is about analysing Bitcoin price data and predicting future Bitcoin prices using an LSTM model. I used historical BTC-USD data from 2015 to 2023 for this project.

The main purpose of this project is to understand how Bitcoin prices have changed over the years and use previous price data to predict future prices.

## Dataset

The dataset contains historical Bitcoin price information such as:

* Date
* Open price
* High price
* Low price
* Close price
* Adjusted close price
* Volume

I used this data to analyse Bitcoin price changes and train the prediction model.

## What I Did

First, I loaded the Bitcoin dataset and checked the data, including its shape, data types, basic statistics and missing values.

After that, I performed exploratory data analysis to understand Bitcoin price movements. I compared opening and closing prices and also analysed the highest and lowest prices for different months and years.

I created different graphs to understand how the Bitcoin price changed between 2015 and 2023.

For the prediction part, I mainly used the Bitcoin closing price. The data was scaled using MinMaxScaler and then divided into training and testing data.

I used an LSTM (Long Short-Term Memory) model because it is useful for working with time-series data.

## Model

The LSTM model was created using TensorFlow and Keras.

The model uses previous Bitcoin closing prices to learn the price pattern and make predictions.

The model was trained for 200 epochs with a batch size of 32.

## Model Evaluation

After training the model, I compared the actual Bitcoin prices with the predicted prices.

I used different evaluation methods such as:

* RMSE
* MSE
* MAE
* R² Score
* Explained Variance Score

I also created graphs to compare the actual and predicted Bitcoin prices.

## Future Prediction

Finally, I used the trained LSTM model to predict Bitcoin closing prices for the next 30 days.

This prediction is based only on the historical data and patterns learned by the model, so it should not be considered financial advice.

## Tools and Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Plotly
* Scikit-learn
* TensorFlow
* Keras

## How to Run

1. Download or clone this repository.
2. Install the required Python libraries.
3. Keep the Bitcoin CSV dataset in the same project folder.
4. Open the Jupyter Notebook.
5. Run the cells one by one.

## Conclusion

Through this project, I learned how to work with time-series data and analyse historical Bitcoin prices. I also learned how to prepare data for an LSTM model, train the model, evaluate its performance and use it to make future predictions.

This project helped me improve my skills in Python, data analysis, data visualization, machine learning and deep learning.

## Author

**Mohammad Althaf Ali**
