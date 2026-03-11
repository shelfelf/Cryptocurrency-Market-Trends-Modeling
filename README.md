Project Overview 

This project investigates the extreme volatility and market trends of cryptocurrencies over a ten-year period. By analyzing daily price points for major coins and altcoins, the study develops a robust classification framework to identify Bullish, Bearish, and Sideways market environments. 

Key Objectives 

Market Trend Classification: Develop a model to accurately predict market shifts based on a 30-day rolling percentage change. 

Technical Indicator Evaluation: Analyze the effectiveness of various indicators (RSI, OBV, ADX, EMA, etc.) across major historical events like the 2017 ICO Boom and the 2021 Market Crash. 

Predictive Performance: Compare individual and ensemble machine learning algorithms to achieve high classification accuracy. 

Historical Events Analyzed 

The project evaluates model performance and market behavior during six critical periods: 

2016 BTC Halving: Analysis of post-halving price surges. 

2017 ICO Boom: Capturing strong capital inflows using On-Balance Volume (OBV). 

2018 Market Crash: Utilizing Average True Range (ATR) to measure volatility post-split. 

COVID-19 Impact (2020): Measuring the strong correlation between BTC and altcoins during the global pandemic. 

2021 Market Crash: Using Exponential Moving Averages (EMA) to track rapid price corrections. 

2024 BTC Halving: Analyzing modern market anticipation and supply-demand shifts. 

The Dataset 

Source: Kaggle (Top 1000 Cryptos Historical). 

Timeline: January 1, 2015 – December 31, 2024. 

Scope: 36,500 unique data points across attributes including Open, Close, High, Low, and Volume. 

Machine Learning Framework 

A refined feature set including RSI (7/14), ADX, SMA 200, and ATR was used to train the following models: 

XGBoost: High performance for capturing complex, non-linear relationships. 

Random Forest: Excellent for handling structured data and reducing overfitting. 

Voting Classifier (Ensemble): A soft-voting approach combining both models to stabilize predictions, achieving up to 87% F1-score for sideways market detection. 

Key Findings 

Best Predictor: The Relative Strength Index (RSI_14) was identified as the most significant feature for trend prediction in both XGBoost and Random Forest models. 

Market Behavior: The ensemble model is most effective at identifying "Sideways" markets (87% F1-score) but faces challenges with "Bearish" periods due to data imbalance. 

Technologies Used 

Python: Pandas, NumPy (Data Processing). 

Visualization: Matplotlib, Seaborn. 

Machine Learning: Scikit-learn, XGBoost. 
