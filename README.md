# Myntra_HackRamp_2024

Fashion Trend Demand Forecasting
Overview
This project aims to predict fashion trends' popularity using real-time customer feedback from social media platforms like YouTube and Instagram. Leveraging sentiment analysis and time series forecasting, the model identifies and forecasts the trends that resonate most positively with consumers. A Streamlit application provides a real-time visualization of sentiment trends and forecasts.

Table of Contents
Overview
Features
Data Collection
Sentiment Analysis
Trend Identification
Time Series Analysis
Streamlit Application

Features
Data Collection: Extract trend names, customer comments, and timestamps from YouTube and Instagram.
Sentiment Analysis: Use Naive Bayes and BERT models to analyze customer sentiment.
Trend Identification: Aggregate sentiment scores to identify trends with the highest positive sentiment.
Time Series Analysis: Use ARIMA to forecast trend popularity durations.
Streamlit Application: Interactive dashboard to visualize real-time sentiment trends and forecasts.
Data Collection
Data is collected from YouTube and Instagram using API integrations. For initial model development and testing, a dummy dataset is used.

Sentiment Analysis
Two models are used for sentiment analysis:

Naive Bayes: Efficient for processing large datasets.
BERT: Excels in analyzing complex sentiments.
The sentiment analysis process involves:

Extracting comments from the dataset.
Preprocessing text (tokenization, removing stop words).
Analyzing sentiments using Naive Bayes and BERT.
Averaging predictions from both models for robust accuracy.
Trend Identification
Sentiment scores are aggregated to identify trends with the highest positive sentiment, enabling brands to focus on consumer-preferred trends.

Time Series Analysis
The ARIMA model is used for time series analysis due to its effectiveness with sequential data and independence from seasonal patterns. Steps include:

Collecting time-stamped sentiment data.
Fitting the ARIMA model to historical data.
Forecasting future trend popularity.
Streamlit Application
An interactive Streamlit application provides real-time sentiment trends and forecasts. Features include:

Real-time sentiment analysis dashboard.
Weekly sentiment trends visualization.
Detailed sentiment trajectory for selected trends.
Forecasts for future trend sentiment over a specified period.
