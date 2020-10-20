# Arvato_Customer_Segmentation
## Capstone Project
### Arvato: Customer Segmentation and Prediction

### Installation

Besides the libraries included in the Anaconda distribution for Python 3.6 the following libraries have been included in this project:

    XGBoost - optimized distributed gradient boosting library designed to be highly efficient, flexible and portable.
    skopt - simple and efficient library to minimize (very) expensive and noisy black-box functions.

### Introduction

This project was made available for Udacity by Arvato. The goal is to find if there are particular patterns in individuals based on collected data that makes them more likely to be responsive to a mail-order campaign by Arvato for the sale of organic products.

The project is divided in 2 sections:

    Customer Segmentation Report (Unsupervised Learning): For this portion of the project I performed EDA, PCA and clustering analysis (KMeans) to identify clusters that are good descriptors for what makes a core customer for this particular Arvato's client.

    Predict Customer Report (Supervised Learning): using the provided data on how customers responded to a marketing campaign I created a model that predicts how particular individuals would respond to campaign.

### Background

This project provided by Arvato Financial Solutions was one of the available capstone projects. I chose this project mainly for several:

    It is a real-world problem in which the data had nearly no transformation, making it a chance for an intensive experience with data processing.
    Customer segmentation is one of the fields in data science and machine learning that is continuously growing and progressing, having this hands-on experience can be very valuable for future problems.
    Since it has a Kaggle competition portion it allows me to measure the success of my efforts against others.

### Datasets

* Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).

* Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).

* Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).

* Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

* DIAS Attributes - Values 2017.xlsx: is a detailed mapping of data values for each feature in alphabetical order.

#### Created by me:

* Arvato Project Workbook.ipynb: notebook where the population and customer data are exploered to gain familiarity with the data.

* Unsupervised Learning.ipynb: notebook where I use the unsupervised learning techniques to cluster the data to segment was portion of the population data fit our current customer data.

* Supervised Learning Model.ipynb: where I create the model that predicts the labels for the test data.

### Instructions

The datasets available in this project is proprietary and as such cannot be share without the authorisation of Arvato.

### Results

I did identify clusters of relevance of future customers and identified positive responders to the mail-order campaign successfuly, pleased read the attached report for an extensive discussion.

Licensing, Authors, Acknowledgements
