# Machine-Learning-For-Rent-Prediction
🏠 Machine Learning Model for Predicting Rental Prices in the U.S.

A data-driven analysis of U.S. rental prices using exploratory data analysis (EDA), feature engineering, and multiple regression and tree-based machine learning algorithms.
This project identifies the key economic, geographic, and demographic drivers of rent, compares model performance, and builds a predictive system for estimating fair market rental prices.

📘 Project Overview

Rental prices fluctuate due to macro-economic factors, regional dynamics, and housing supply/demand shifts. This project analyzes ~100,000 rental listings across the U.S. to uncover the strongest predictors of rental prices and build a machine learning model capable of estimating rent with high accuracy.

The objective is to help:

Renters understand fair pricing

Property owners set optimal rates

Real estate firms identify profitable markets

Policy makers better understand affordability trends

(See detailed report → Rent Prediction Model.pdf) 

Rent Prediction Model

📊 Dataset & Features

The dataset contains economic, spatial, and property-level variables:

Property Features

Square footage

Number of bedrooms

Number of bathrooms

Geospatial Features

Latitude

Longitude

Region (West, Southeast, Northeast, Midwest, South)

Economic & Demographic Features

GDP per capita (by state)

State population

Crime rate

School expenditure per capita

These features were used to identify correlations and build predictive models.

🔍 Exploratory Data Analysis (EDA)
Key EDA Components

Outlier removal using ±3 standard deviations (see page 7 histogram)

Correlation heatmaps for feature relationships

Price distribution by region

Identification of top 20 most expensive states

Geographic visualization of listings across the U.S.

Insight Examples:

Rental prices vary widely by region, with DC, NJ, and RI being the most expensive (pages 18–19).

GDP per capita and square footage show strong positive correlation with rent (page 21).

Crime rate shows mixed impact depending on region.

Visual references appear throughout the report: 

Rent Prediction Model

🤖 Machine Learning Models

Three models were trained and compared:

1️⃣ Polynomial Regression (Degree = 4)

R² = 0.65

Captures non-linear relationships

No multicollinearity (VIF < 5 for all variables)

2️⃣ Decision Tree Regressor

R² = 0.75

Feature importance highlights GDP per capita and square footage

Visual tree structure included (page 11)

3️⃣ Random Forest Regressor (Best Model)

R² = 0.85

Strongest performance with lowest error

Robust to outliers and non-linear patterns

Actual vs. predicted plot (page 15) shows excellent alignment

A comparison table of accuracy is included on page 22 of the PDF.

📈 Winner: Random Forest Regressor

🧠 Key Findings
Top Predictors of Rent

Based on feature importance across models:

GDP per capita (strongest driver)

Square footage

Latitude / Longitude (hidden geographic effects)

Crime rate

Population density

Regional Pricing Insights

Northeast and West show the highest median rental prices.

The South and Midwest remain the most affordable regions.

Violent crime rate exhibits a negative correlation with rent in many markets (page 20).

Economic Insight

Higher-GDP regions consistently have higher rent, regardless of population or crime levels.

🛠 Tech Stack

Languages & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

🎯 Practical Impact
For Renters

Helps assess whether a listing is overpriced

Supports better negotiation and budgeting

For Property Owners

Sets competitive & optimized pricing

Reduces vacancy rates

For Real Estate Firms

Identifies undervalued markets

Improves investment decisions

For Government / Policy Makers

Informs affordability and urban-planning policies

(See use-case visualizations on pages 23–25.)

🧠 My Contributions

Conducted EDA, outlier detection, and data preprocessing

Developed multiple ML models and compared performance

Built Random Forest model achieving R² = 0.85

Interpreted features and regional trends

Created full analytical PDF report for stakeholder review

🚀 Future Enhancements

Add time-series forecasting for rent trends

Train XGBoost or CatBoost models for deeper non-linear insights

Add neighborhood-level census data

Build a predictive dashboard or web app for real-time rent estimation

[RENT PREDICTION MODEL ANALYTICAL REPORT.pdf](https://github.com/user-attachments/files/24156410/RENT.PREDICTION.MODEL.ANALYTICAL.REPORT.pdf)

   
