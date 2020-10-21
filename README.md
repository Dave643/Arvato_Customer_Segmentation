# Arvato_Customer_Segmentation
## Capstone Project: Arvato: Customer Segmentation and Prediction

###Publicaions:
[1] https://medium.com/@davidkimani1/customer-segmentation-marketing-customer-mailout-campaign-target-61ffdc82be64

### Installation

Besides the libraries included in the Anaconda distribution for Python 3.6 the following libraries have been included in this project:

* XGBoost - optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.
* skopt - simple and efficient library to minimize (very) expensive and noisy black-box functions.

### Introduction

This project was made available for Udacity by Arvato. The goal is to find if there are particular patterns in individuals based on collected data that makes them more likely to be responsive to a mail-order campaign by Arvato for the sale of organic products.

TThe work presented here is in two parts:

1. Customer Segmentation Report (Unsupervised Learning): PCA and clustering analysis (KMeans) provides clusters of current customers and population data provided.  When the clusters are compared this gives a good indication of the people in the population that we can focus who mostly fit the majority of our current customers.

2. Predict Customer Report (Supervised Learning): This is the prediction stage for the project where we take in the training data, produce a model and predict the likelyhood that the people in the test dataset are to become customers following the mail-order campaign.

### Background

This project support the Arvato Financial Solutions was one of the available capstone projects for the Udacity datascience nanodegree.  

We get a real world problem where the data has almost no transformation, giving an oppotunity with data processing, dimentinality reduction and the challenges that comes with imbalanced data.

Customer segmentation can be better designed using data science machine learning techniques which one of the fields in data science and machine learning that is continuously growing and progressing, having this hands-on experience can be very valuable for future problems.

This project has a Kaggle competition that gives an oppotunity to measure how I am doing against others.

### Datasets

* `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).

* `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).

* `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).

* `Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

* `DIAS Attributes - Values 2017.xlsx`: is a detailed mapping of data values for each feature in alphabetical order.

#### Created by me:

* `Arvato Project Workbook.ipynb`: notebook where the population and customer data are exploered to gain familiarity with the data.

* `Unsupervised Learning.ipynb`: notebook where I use the unsupervised learning techniques to cluster the data to segment was portion of the population data fit our current customer data.

* `Supervised Learning Model.ipynb`: where I create the model that predicts the labels for the test data.

* `Capstone Project Report.pdf`: this report documents the work done for the completion of this project.

### Instructions

The datasets available in this project is proprietary and as such cannot be share without the authorisation of Arvato.

### Results

The unsupervised segment identifies clusters of potential future customers and identified positive responders to the mail-order campaign.

Attahced report further discusses the wprk carried out.

Licensing, Authors, Acknowledgements
