# Bike Demand Prediction using Linear Regression

## Project Overview
This project aims to predict the daily demand for shared bikes in Washington D.C. using a Linear Regression model. The dataset includes features such as weather conditions, season, holidays, and working days. The objective is to help BoomBikes, a bike-sharing company, understand demand patterns and optimize their operations post-COVID.

## Objectives
- Analyze patterns in historical bike rental data
- Perform data cleaning and feature engineering
- Visualize data to understand trends and relationships
- Build and evaluate a multiple linear regression model
- Identify key factors that influence bike demand
- Provide actionable insights for business decision-making

## Dataset
The dataset `day.csv` contains daily bike rental counts along with associated weather and seasonal information. It was provided as part of a case study scenario by BoomBikes.

## Key Steps
- Exploratory Data Analysis (EDA)
- Outlier detection and treatment
- Variable transformation and encoding
- Feature selection using RFE and VIF
- Model building and interpretation
- Performance evaluation using R² score

## Results
The final linear regression model was able to explain approximately 80% of the variance in daily bike demand. The most significant factors included temperature, season, working day, and weather situation.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Conclusion
The model helps identify critical drivers of bike rental demand and can assist BoomBikes in optimizing fleet size, improving customer satisfaction, and planning future expansions.


