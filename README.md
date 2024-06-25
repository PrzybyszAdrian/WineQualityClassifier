# WineQualityClassifier

A project for predicting wine quality using various machine learning models.

## Overview

This project aims to predict the quality of wine based on its chemical properties. The workflow includes:
1. Loading data from a CSV file.
2. Performing preliminary data analysis.
3. Normalizing the data.
4. Categorizing labels.
5. Training multiple classification models.
6. Fine-tuning the best model.
7. Evaluating model performance.

## Dataset

The dataset used in this project is the Wine Quality Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).

## Explanation of Label Categorization

Instead of vectorizing labels, label categorization is applied in this project because the task is to convert a regression problem into a binary classification problem. The wine quality scores are categorized into two labels: "good" (quality >= 6) and "bad" (quality < 6). This categorization simplifies the construction of classification models, which are more suitable for binary classification tasks than for multiclass classification or regression. Vectorization is typically used in text analysis to convert text into numerical features, which is not applicable in this context.

