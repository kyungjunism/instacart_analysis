# Instacart Analysis

Instacart Market Basket Analysis

Which products will an Instacart consumer purchase again?

[Instacart](https://www.instacart.com), a grocery delivery web/app is trying to identify what return customers are likely to order which products. This repository will contain an iPython Notebook which will contain exporatory data analysis and basic information about the given datasets.

The Datasets:
The datasets for the project are made up of relational databases which describe customers' orders over a given time period. The data is anonymized and contains samples of 3 million orders from more than two hundred thousand Instacart users.

Goals:
The goal of the competition is to predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.

In this notebook, we will try and explore the basic information about the dataset given. The dataset for this competition is a relational set of files describing customers' orders over time.

The secondary goal of the project is to predict which products will be in a a return customer's next order and to form a recommendation engine much like Amazon's "Frequently Bought Together" section or Netflix's "Because you watched:" section. A reccomendation engine that suggests particular products from a user's current selection or prior order could potentially help drive more sales and faster checkouts.

Methods Likely to be Used: A regression would most likely be used to see the relationship between what customers are likely to order again while XGBoost may be used for the reccomendation engine.

Deliverables:

The key deliverables for this project will include the iPython Notebook which contains the code for exploratory data analysis, the predictions, and the reccomendation engine. 

[There will be a submission file for the Kaggle Competition as well.](https://www.kaggle.com/c/instacart-market-basket-analysis#evaluation)

#Data Cleaning/Wrangling

As for Data Cleaning, THe bulk of the data was provided through Kaggle with data already cleaned for the project.

However, some tables required data type changes, dropping of null values, and the creation of dummy variables to prepare the data for machine learning.
