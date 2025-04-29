# Uber Trips Analysis

## Overview
Analysis and modeling of Uber ride data (2014–2015) to understand trip demand, peak periods, and optimize driver supply and pricing strategies.

## Objectives
- Explore patterns in trip frequency by time and location.
- Predict hourly demand using machine learning models.

## Workflow
- **Dataset**: NYC Uber pickups (April–Sep 2014), merged monthly CSVs.
- **EDA**: Temporal trends (weekday, hourly, seasonal), base station performance.
- **Feature Engineering**: Lag features, holidays, sine/cosine transforms for time cycles.
- **Models**: Random Forest, XGBoost, LightGBM (Best R²: 0.9814 after tuning).

## Key Insights
- Demand peaks on weekends and around mid-month.
- Paydays are high-demand periods.
- Base B02764 is top performing; B02512 needs improvement.

## Tools
`Python`, `Pandas`, `LightGBM`, `XGBoost`, `Matplotlib`, `Seaborn`
