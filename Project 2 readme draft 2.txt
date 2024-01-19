##Algorithmic Trading Strategy Overview
This repository contains code for an algorithmic trading strategy that leverages machine learning for momentum trading. The strategy is implemented in Python and uses ALPACA API for MSFT stock data. The machine learning component involves the creation of three neural networks to compare their performance.

##Dependencies
Make sure to have the following dependencies installed:

TA-Lib: Library for technical analysis
Alpaca API: API for financial market data
Other Python libraries: pandas, matplotlib, numpy, sklearn, tensorflow, etc.
Ensure you have your own Alpaca API key.

##Getting Started
Install the required dependencies:

##Data Collection:

Alpaca API is used to pull financial market data for MSF.
Additional technical indicators (MACD, RSI, ADX, etc.) are added to the dataset.
##Signal Generation:

Momentum trading signals for buying or selling are generated using the code provided. Verified by ADX. 
##Neural Network Comparison:

Three different neural networks are trained and compared.
X includes all columns in the dataframe except for the target 'y'.
##Analysis and Visualization:

The performance of each neural network is analyzed for accuracy.
Final trade predictions are plotted for visual comparison.
##Results
The machine learning momentum trading strategy compares the performance of three neural networks, providing insights into their accuracy and effectiveness in predicting trade signals.

