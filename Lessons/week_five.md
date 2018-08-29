##### Week 5:
Formulating a Hypothesis About the Data
- Overview of Machine Learning
- Variance/bias tradeoff
- Scikit Learn's `linear_model` module
- One hot encoding to use categorical variables in a model
- Creating training and test data
- Coding tasks:
    - What does the exploratory data analysis suggest about our question?
    - Create a seaborn pairplot to look at correlations between variables in the data.
        - first drop the fips column, all columns related to confidence intervals, and columns for years 2010 and 2014
        - are there any linear relationships suggested by the pairplot? 
    - Select explanatory variables that may predict a target. You can use the cancer death rate per 100,000 people as a target or come up with your own.
    - Use `pd.get_dummies()` with your explanatory variables to encode any categorical values.
    - Split to train and test sets.
    - build and evaluate a linear model.

    