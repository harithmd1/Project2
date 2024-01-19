Algorithmic Trading Strategy Overview
This repository contains code for an algorithmic trading strategy that leverages machine learning for momentum trading. The strategy is implemented in Python and uses ALPACA API for MSFT stock data. The machine learning component involves the creation of three neural networks to compare their performance.

Dependencies
Make sure to have the following dependencies installed:

TA-Lib: Library for technical analysis
TextBlob: Library for sentiment analysis
Alpaca API: API for financial market data
Other Python libraries: pandas, matplotlib, numpy, sklearn, tensorflow, etc.
Getting Started
Install the required dependencies:


Copy code
pip install TA-Lib
pip install textblob
pip install alpaca-trade-api
Ensure you have your own Alpaca API key.

Clone this repository:
Copy code
https://github.com/harithmd1/Project2
cd Project2
Open the Jupyter notebook or Python script containing the algorithm.

Usage
Data Collection:

Alpaca API is used to pull financial market data for GOOGL.
Additional technical indicators (MACD, RSI, ADX, etc.) are added to the dataset.
Signal Generation:

Momentum trading signals for buying or selling are generated using the code provided.
Neural Network Comparison:

Three different neural networks are trained and compared.
X includes all columns in the dataframe except for the target 'y'.
Analysis and Visualization:

The performance of each neural network is analyzed for accuracy.
Final trade predictions are plotted for visual comparison.
Results
The machine learning momentum trading strategy compares the performance of three neural networks, providing insights into their accuracy and effectiveness in predicting trade signals.

