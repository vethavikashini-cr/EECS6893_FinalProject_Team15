#   Stock Price Prediction Based on Sentiment Analysis

## Objectives- 
Handling significantly large data and predicting the nature of changing stocks
To effectively compare different ML models by using ensemble learning
To see the nature of deep learning models used in short-term and long-term cases
Comparatively analyzing their accuracies to glean an understanding of their performance

## Data- 
### Twitter Data: Twscrape: An open-source library that scrapes relevant tweets according to company.
Data is fetched using 25 API calls company-wise for each day by filtering out any links, media, and replies. 

### Preprocessing pipeline-

<img width="462" alt="image" src="https://github.com/vethavikashini-cr/EECS6893_FinalProject_Team15/assets/145593646/da248fcf-993a-4bac-a777-fa94f53f5c58">


### Stock Data: 
Extract the stock price and volumes since  2021 01-01, i.e 3 years approx by selecting 3 companies: Google, Amazon and Microsoft

Used the Technical Analysis Package to add more indicators and performed PCA

## Models Used-
Random Forest, Ada Boost, Linear Regression and LSTM

## System Overview:

![image](https://github.com/vethavikashini-cr/EECS6893_FinalProject_Team15/assets/145593646/e0a5579f-a191-4fc2-b345-31eb94721dca)

# Authors
### Balachander Sathianarayanan

### Swasthi P Rao

### Vethavikashini Chithrra Raghuram
