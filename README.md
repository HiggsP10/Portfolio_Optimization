# Deep learning for portfolio optimization 
This project contains the final project of May-Summer 2024 Deep Learning Boot Camp

## Overview
This project focuses on developing advanced models for selecting an optimal mix of stocks to maximize returns while minimizing risk, tailored to an investor's risk tolerance, investment goals, and market conditions. The project explores both short-term and long-term portfolio optimization strategies:

- **Short-Term Portfolio Optimization**: We leverage sentiment analysis using the BERT language model in conjunction with the Black-Litterman model to perform dynamic portfolio optimization over a 10-day horizon. This approach allows for more responsive adjustments to changing market conditions and investor views.
- **Long-Term Portfolio Optimization**: For longer investment horizons, we implement a Long Short-Term Memory (LSTM) network as a deep learning model to predict stock performance. The LSTM model is compared with the Markowitz Mean-Variance Model and Genetic Algorithm to assess its effectiveness in constructing a well-diversified portfolio that balances risk and return over the long term.

By combining these different approaches, this project aims to provide a comprehensive toolkit for portfolio optimization, addressing various market environments and investment objectives.
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

