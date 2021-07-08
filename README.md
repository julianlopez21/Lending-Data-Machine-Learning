# Lending Data Machine Learning

In this project I compared the effectiveness of several machine learning models to predict credit risk using a sample of peer-to-peer lending service data.

## Resampling

First, I ran a simple logistic regression and compared the performance to a number of different resampling methods: 
- Oversampled the data using imblearn's Naive Random Oversampler 
- Oversampled the data using imblearn's SMOTE algorithim
- Undersampled the data using imblearn's Cluster Centroid algorithm
- Combination of oversampling and undersampling using imblearn's SMOTEEN algorithm

For each method, I created and compared the following metrics:
- Balanced Accuracy Score (sklearn)
- Confusion Matrix (sklearn)
- Imbalanced Classification Report (imblearn)

Ultimately, I found that SMOTE Oversampling was the most effective method of resampling for this set of data.

## Ensemble Learning
