# Coordinating 

This is so that we're hopefully all on the same page 

Looking at the pdf for the paper we said we were going to replicate

## Problem we are addressing 
Forecasting future earnings of large cap stocks

- Using Time series data


## Models to apply
We need to apply 4 models to this problem as requested by the project

1. Recurrent Neural Network
    - This is discussed at length in the paper where we got our problem from
    - Trained using a deep network

2. Random Forest Regressor
    - Can be applied to a time series for a direct prediction

3. K-means clustering and markov chains
    - identify differenent regimes using our TS data and use a markov chain to make forecasts for future regimes
    - See if we can find clusters that correlate with different earnings outcomes 

4. Gradient Boosted Regressor Trees
    - XGboost