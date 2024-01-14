# Fake News Detection using Logistic Regression

## Overview
This project aims to identify false news using a dataset obtained from Kaggle. The dataset contains five fields: Id, Author name, News Title, News, and the label (indicating whether the news is true or false in 0/1 form). The model utilizes Logistic Regression for classification based on the title and author.

## Data Cleaning and Preprocessing

- Empty fields are checked and null values are replaced with an empty space.
- The News Title and Author are combined to form a new column.
- Stemming is applied to the content column, returning the root word of each word.
- The content column is converted into a list to remove stop words.

## Text to Numeric Conversion

- Tfidf Vectorizer is applied to convert textual data into numerical form.
- Data is split into training and test sets, with a testing size of 20%.

## Model Training
- Logistic Regression is chosen as the machine learning model.
- The training data is fed into the Logistic Regression model for training.
