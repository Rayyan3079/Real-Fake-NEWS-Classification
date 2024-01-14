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

## Screenshots

![image](https://github.com/Rayyan3079/News/assets/124567636/beb07ab0-e6eb-4c27-83a8-006d4716b585)
![image](https://github.com/Rayyan3079/News/assets/124567636/e4e07666-a984-4f8c-b1cf-aa7fc364e25a)
![image](https://github.com/Rayyan3079/News/assets/124567636/4f6c34cc-234e-47e1-be19-e892c1b2a663)



