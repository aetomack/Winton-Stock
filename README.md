# Overview
Predict the return of a stock, given the history of the past few days. 

# Provided
- 5-day windows of time, days D-2, D-1, D, D+1, and D+2. 
- Returns in days D-2, D-1, and part of day D.

# Task
Predict the returns in the rest of day D, and in days D+1 and D+2.

# Pointers
During day D, there is intra-day return data, which are the returns at different points in the day. We are provided 180 minutes of data, from t=1 to t=180. In the training set, we are given the full 180 minutes, in the test set just the first 120 minutes are provided.

For each 5-day window, we are provided 25 features-- Feature_1 to Feature_25. May or may not be useful.

Each row in the dataset is an arbitrary stock at an arbitrary 5 day time window.
