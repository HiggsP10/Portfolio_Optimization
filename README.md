# Deep learning for portfolio optimization 
This project contains the final project of May-Summer 2024 Deep Learning Boot Camp

## Overview
This project aims to develop models to select the best possible mix of stocks to maximize returns while minimizing risk, based on an investor's risk tolerance, investment goals, and market conditions. Sentiment analysis by using BERT language model.
## Dataset
We picked interested tickers = ['AAPL', 'AMZN', 'COST', 'DIS', 'GOOGL', 'JPM', 'LLY',  'MSFT','META', 'NFLX', 'NVDA', 'TSLA'], then pulled related stock data from following
- Stocks market data from Yahoo Finance 
- Sentiment analysis data from ~5000 Tweets
- [Hugging Face News Data](https://huggingface.co/datasets/okite97/news-data)
- AlphaVantage Stock Data
  
The visulization of the correlation matrix
![image](https://github.com/user-attachments/assets/561ff6d0-ee4e-46aa-8451-d05ac68e70f3)

## Modeling Approach
- [ref](https://link.springer.com/article/10.1007/s00521-022-07403-1) The Black-Litterman model with sentiment analysis: notebooks/BL_alphavantage_modify.ipynb
- Long-Short-Term-Memories Network: notebooks/LSTM.ipynb
- Markowitz Mean-Variance Model: notebooks/MeanVariance.ipynb
- Genetic Algorithm: notebooks/GeneticAlgorithm.ipynb

