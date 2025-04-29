# Customer Satisfaction Prediction

## Overview
A machine learning approach to predict customer satisfaction based on support tickets from a tech product company. Focus on identifying key drivers of satisfaction and optimizing service channels.

## Objectives
- Understand customer issues and channel usage.
- Predict satisfaction scores from closed support tickets.

## Workflow
- **Dataset**: Tech product customer support tickets.
- **EDA**: Issue types, resolution times, channel use, and demographic trends.
- **Preprocessing**: Label encoding, TF-IDF on descriptions, handling mislabeled fields.
- **Feature Engineering**: Ticket length, keyword frequency, SMOTE for class balancing.
- **Models**: Random Forest (Best: 58% accuracy), Logistic Regression, Neural Network (MLP).

## Key Insights
- Phone support yields highest satisfaction.
- Resolution time negatively correlates with satisfaction.
- Data labeling issues hurt model performance.

## Tools
`Python`, `Pandas`, `Scikit-learn`, `TF-IDF`, `SMOTE`, `Seaborn`
