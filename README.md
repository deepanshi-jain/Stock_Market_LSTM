<h1 align="center">💰 Stock Market Prediction using LSTM 💸</h1>



<p align="center">
  Welcome to the Stock Market Prediction using LSTM project! This repository contains the code and resources for predicting stock market trends using Long Short-Term Memory (LSTM) neural networks. With the power of deep learning, we aim to forecast stock prices and make informed investment decisions.
</p>

## Project Overview 💡
In this project, we leverage historical stock market data to train an LSTM model. The model learns from past price patterns and trends, enabling it to predict future stock prices. The LSTM network is specifically designed to capture long-term dependencies and has proven to be effective in time series forecasting tasks.

## Dataset 📊
We use a publicly available dataset containing historical stock prices of various companies. The dataset includes features like opening price, closing price, volume, etc. We preprocess the data, splitting it into training and testing sets, and perform any necessary data transformations.🫡

## Model Training 🧑🏻‍💻
The LSTM model is built using deep learning frameworks like TensorFlow or PyTorch. We train the model on the training dataset, adjusting hyperparameters such as the number of hidden layers, the number of neurons per layer, and the learning rate. We employ techniques like regularization and dropout to prevent overfitting.

## Evaluation and Results 📈
Once the model is trained, we evaluate its performance on the testing dataset. We compute various metrics such as mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE) to assess the model's accuracy. We visualize the predicted stock prices alongside the actual prices to gain insights into the model's performance.

## Usage 💪🏻
To run the project locally, follow these steps:
1. Clone this repository
2. No need to download any dataset, this project uses Yahoo finance library to directly fetch data, just write the correct company code.
3. Run the `training code` script in the notebook to train the LSTM model.
4. Run the `predict code` script in the notebook to make predictions on new data.

## Results and Discussion 📊
It present the results of our stock market prediction experiments. We discuss the model's performance, its strengths, limitations, and potential areas of improvement. We also provide visualizations of the predicted stock prices and compare them with the actual prices.

![alt text](<Screenshot 2025-07-13 213634.png>)

R² Score: 0.91 (indicates that 91% of the variance in stock price movements is explained by the model)
RMSE: 14.92 (low error indicating high accuracy)
