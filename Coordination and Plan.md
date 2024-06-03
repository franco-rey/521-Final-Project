# Coordinating 

This is so that we're hopefully all on the same page 

## Final Push Gameplan
    - Outline your markdown cells for the final report in `group report -OUTLINE FOR WRITING.ipynb`
    - avoid editing the main group report directly until we are combining work in the final report
    - Get everything you can ready for your model in the meantime, we are only working with continuous variables
        - e.g. pipelines, numerical preprocessing required for your model, hyperparameter tuners if needed, helper functions to plot centroids
        - cont. selecting proper scores/metrics, writing why they are theorectically good choices
    - We are using the features discussed in the white paper minus accruals so only continuous numeric features
    - You should be able to prepare a decent amount of this even without the prepared data quite finalized just yet
    
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
  