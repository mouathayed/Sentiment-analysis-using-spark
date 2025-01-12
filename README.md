# Twitter Sentiment Analysis Using PySpark

## Project Overview
This repository contains a PySpark implementation for analyzing Twitter sentiment based on the [Sentiment140 dataset from Kaggle](https://www.kaggle.com/kazanova/sentiment140). The project utilizes Logistic Regression, Naive Bayes, and SVM models to classify sentiments as either positive or negative.

## Features
- **Data Processing**: Utilizes PySpark for robust data preprocessing and cleaning, and incorporates SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset, enhancing the model's performance on underrepresented classes.
- **Sentiment Classification**: Employs Logistic Regression, Naive Bayes, and SVM models.
- **Performance Evaluation**: Models are assessed using accuracy, precision, recall, and Area Under the ROC Curve (AUC).