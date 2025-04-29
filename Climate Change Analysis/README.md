# Climate Change Analysis

## Overview
This project analyzes public sentiment around climate change using Facebook comments from NASA’s climate page (2020–2023). It combines sentiment analysis, trend analysis, and topic modeling to uncover public opinion patterns and engagement drivers.

## Objectives
- Classify sentiment in user comments (positive, neutral, negative).
- Analyze trends and engagement patterns.
- Discover underlying discussion topics using topic modeling.
- predict future co2 emissions, temperature anamolies, sea-level rise and extreme weather conditions.

## Workflow
- **Dataset**: `climate_nasa.csv`
- **Text Preprocessing**: Handled missing data, cleaned text, used TextBlob for polarity.
- **Feature Engineering**: TF-IDF vectorization, sentiment labeling.
- **Models**: SVM (best: 89.7% accuracy), Random Forest, Logistic Regression, Gradient Boosting.
- **Topic Modeling**: Used LDA with CountVectorizer (5 topics).
- **Trend Forecasting**:
  - CO₂ prediction (Linear Regression: R² ≈ 0.996)
  - Temperature Anomalies (SARIMAX, XGBoost)
  - Sea Level Rise (Linear Regression: R² ≈ 0.91)
  - Extreme Weather (XGBoost Classifier)

## Key Insights
- Sentiment is mostly neutral; questions and controversial content drive engagement.
- CO₂ and temperature trends indicate worsening climate conditions.
- Higher probability of extreme weather events in the future.

## Tools
`Python`, `Pandas`, `TextBlob`, `Scikit-learn`, `XGBoost`, `SARIMAX`, `LDA`, `Matplotlib`

