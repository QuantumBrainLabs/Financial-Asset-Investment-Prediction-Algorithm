# Financial-Asset-Investment-Prediction-Algorithm
## MSc Deep Learning Final Project

Welcome to the repository for our Master's final project, where we present an algorithm designed to determine whether it's advisable to invest in financial assets for the next day. This README will guide you through the project structure, environment setup, functionalities, and usage.

## Objective

Our main goal was to develop and present a revolutionary algorithm based on artificial intelligence, capable of analyzing and detecting patterns in the financial assets of the stock market. Through this decision algorithm, we sought to develop an accurate and reliable tool to make informed buy and sell decisions, thus maximizing profits and taking advantage of opportunities in the dynamic world of the stock market.

  <div align="center">
    <img src="https://s10.s3c.es/imag/_v0/770x420/d/0/5/600x400_buy-sell-dados.jpg" alt="data-analysis"/>
  </div>

## Generating Function

It was the basis of our code from which we gave the user the option to place:

Collect historical stock price data using the "yfinance" library for each of the specified symbols.
Calculates daily percentage change, daily logarithmic returns and other technical metrics such as SMA, EMA, MACD, RSI, Stochastic Oscillator, ATR, Bollinger Bands, VWAP, OBV, CMF, CCI, ROC, among others.
Generates signals or indicators (flags) based on the calculated metrics, which indicate bullish, bearish or neutral trends or patterns in stock prices.
Identifies candlestick patterns in stock prices using various functions of the "talib" library.
Generates a "Target" column that indicates whether to buy, sell or do nothing based on a specified percentage threshold.
Optionally, normalizes the data using the MinMaxScaler
Splits the data into training, validation and test sets for further analysis and modelling.

![holi](https://github.com/QuantumBrainLabs/Financial-Asset-Investment-Prediction-Algorithm/assets/87869947/ec9090a1-d07e-4550-b855-9ccc4710668d)

## Models

### Recurrent Neural Networks
As used in time series analysis. Since financial data is often sequential, RNNs can capture complex temporal patterns. Using architectures such as LSTM(Long Short-Term Memory)

### Neuronal Networks
Where we normalize the data and apply two layers of 90 neurons, one with "relu" activation and the third with "softmax".

### Random Forest
Although we had been working with Tensorflow, we also wanted to try this type of sickit-learn model.  We also wanted to try this type of sickit-learn model since we were facing a classification problem.

### Support Vector Machine
Having already applied a Random Forest, we moved on to the SVM, where we could regulate the layers and make the model more complex and thus look for better results.

### Convolutional Neural Networks
Here it was interesting, wanting to break a little with the matrix and after some discussion, we decided to make a convolutional where, instead of images, we passed a set of data grouped by a certain amount of time.

## Feel free to reach out if you have any questions or need assistance. Happy investing! 🚀📈
