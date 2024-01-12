# Fake-News-Prediction-Using-Machine-Learning-With-Python
This repository contains a machine learning project that aims to predict whether news articles are fake or real.
# Fake News Prediction Project

## Overview
This project aims to predict whether a given news article is real or fake using machine learning techniques. A logistic regression model is trained on a dataset of labeled news articles to make predictions.

## Project Structure
- **data**: Contains the dataset used for training and testing.
- **notebooks**: Jupyter notebooks for data analysis, model development, and evaluation.
- **src**: Python scripts for data preprocessing, model training, and prediction.
- **README.md**: Project documentation providing an overview and basic instructions.

## Data Cleaning

1. **Remove Duplicates and Missing Values:**
   - Utilize Pandas to identify and remove duplicate rows.
   - Handle missing values appropriately, either by imputation or removal.

2. **Text Data Cleaning and Stemming:**
   - Perform text preprocessing on news content.
   - Apply stemming to reduce words to their root form.
   - Techniques such as stemming, lowercase conversion, and removal of non-alphabetic characters.

## Model Development

1. **Text Vectorization:**
   - Use TF-IDF Vectorizer to convert textual data into numerical features.

2. **Train-Test Split:**
   - Split the dataset into training and testing sets using `train_test_split`.

3. **Logistic Regression Model:**
   - Implement a logistic regression model using scikit-learn.

4. **Model Training:**
   - Fit the model to the training data.

## Model Evaluation

1. **Accuracy on Training Data:**
   - Evaluate the model's accuracy on the training dataset.

2. **Accuracy on Test Data:**
   - Evaluate the model's accuracy on the test dataset.

3. **Prediction and Interpretation:**
   - Make predictions on new data points and interpret the results.

## Description
![flow chart of fake news prediction](https://github.com/anoopalexz/Fake-News-Prediction-Using-Machine-Learning-With-Python/assets/99873291/1b57a976-99d0-4ec8-a18a-75f2a9b6e404)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/anoopalexz/fake-news-prediction.git
   cd fake-news-prediction
