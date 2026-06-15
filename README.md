# Airline Customer Satisfaction - Logistic Regression

## Project Overview
This project analyzes airline passenger survey data using Python 
and Scikit-learn to build a Logistic Regression classification 
model to predict customer satisfaction.

## Dataset
- Source: Invistico Airline Survey
- Size: 129,880 passengers, 22 features
- Target: satisfaction (satisfied/dissatisfied)

## Modeling Approach
- Encoded categorical variables using LabelEncoder
- Scaled features using StandardScaler
- Split data 80/20 train/test
- Built Logistic Regression model with Scikit-learn

## Model Performance
- Accuracy:  83%
- Precision: 84.2%
- Recall:    84.3%

## Key Drivers of Satisfaction
1. Online boarding experience
2. Inflight wifi service
3. Type of travel (business vs leisure)
4. Inflight entertainment
5. Seat comfort

## Recommendations
1. Improve online boarding experience
2. Invest in inflight wifi quality
3. Enhance inflight entertainment options
4. Focus on business class seat comfort
5. Target retention strategies at leisure travelers

## Environment Setup
pip install pandas numpy matplotlib seaborn scikit-learn

## Files
- logistic_regression_analysis.ipynb - Main analysis notebook
- Invistico_Airline.csv - Dataset
