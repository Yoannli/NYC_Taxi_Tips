# Analysis of Tip Amounts in New York City
This repository contains data analysis and processing, and training a model to predict the tip amount to yellow taxi drivers in New York based on several factors. The dataset is taken from https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

The code is split up in 4 python notebooks:
* 1_merge_datasets.ipynb
    * information about the datasets
    * read the datasets 
    * merge the datasets (taxi trips and weather conditions)
* 2_eda_featureeng.ipynb
    * data cleaning (outliers, irrelevant data entries, etc.)
    * exploratory data analysis
    * feature engineering
* 3_feature_selection.ipynb
    * analyse importance of each feature
    * perform feature selection
* 4_model.ipynb
    * train and test models
    * KNN, SVM, Logistic Regression, Neural Network
    * Improving final model
