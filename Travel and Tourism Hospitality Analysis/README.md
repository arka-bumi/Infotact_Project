# Travel, Tourism & Hospitality - Customer Retention and Dynamic Pricing Analysis

## Project Overview

This project focuses on analyzing hotel booking data to identify customer cancellation behavior and dynamic pricing trends within the hospitality industry.

The primary objective is to uncover factors contributing to booking cancellations and to analyze seasonal pricing fluctuations using Exploratory Data Analysis (EDA), and business-driven insights. additionally, build predictive models (Logistic Regression and Decision Tree) to forecast booking cancellations and minimize revenue loss.

The project supports strategic decision-making for:
- customer retention
- revenue optimization
- demand forecasting
- and dynamic pricing strategies

# Business Problem

Hotels and travel businesses often face:
- High booking cancellation rates
- Unpredictable customer behavior
- Revenue loss from cancellations
- Difficulty optimizing room pricing dynamically

The objective is to identify:
- Why customers cancel bookings
- Which customer segments are high-risk
- How pricing changes across seasons
- How cancellations affect overall revenue

  
# Project Objectives

- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Analyze customer cancellation trends
- Identify important customer segments
- Evaluate pricing trends using ADR (Average Daily Rate)
- Estimate revenue loss caused by cancellations
- Build a cleaned dataset for future predictive modeling
- Build an interactive cancellation dashboard in Power BI

# Dataset Information

The dataset used:
- Hotel Booking Demand Dataset

The dataset contains hotel booking records including:
- Booking lead time
- ADR
- Customer type
- Market segment
- Hotel type
- Cancellation status
- And booking behavior.

# Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn (sklearn)
- Jupyter Notebook (VS Code)
- Power BI
- Git & GitHub

# Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed sensitive customer information:
  - Name
  - Email
  - Phone Number
  - Credit Card Information 
- Handled missing values in:
  - `children`
  - `country`
  - `agent`
  - `company`
- Corrected datatype inconsistencies
- Investigated duplicate booking records
- Detected and handled outliers in the `adr` column
- Created new business-related features:
  - `total_nights`
  - `total_guests`
  - `revenue`

# Exploratory Data Analysis (EDA)

The EDA focused on identifying factors affecting customer cancellations and revenue patterns.

- Cancellation distribution
- Lead time behavior
- Customer retention patterns
- ADR trends
- Revenue seasonality
- Market segmentation
- Pricing behavior

**Key Findings**
- City hotels showed higher cancellation rates compared to resort hotels.
- Longer lead times were associated with increased cancellation probability.
- Repeated guests demonstrated lower cancellation behavior.
- Deposit requirements reduced cancellation likelihood.
- ADR and revenue displayed strong seasonal patterns.
- Certain customer and market segments exhibited higher churn tendencies.

# Machine Learning Modeling (Predictive Analytics)

In this phase, we developed a predictive model to classify whether a booking is likely to be canceled (is_canceled = 1) or not (is_canceled = 0).  
- Feature Engineering & Encoding: Categorical variables (such as hotel, market_segment, and deposit_type) were transformed into numerical formats using One-Hot Encoding.  
- Data Splitting: The dataset was split into an 80% training set and a 20% testing set.  
- Algorithms Evaluated: We implemented and evaluated Logistic Regression and Decision Tree Classifier models. 
- Model Performance (Logistic Regression): Accuracy 79%; ROC-AUC Score 0.8295; Precision (Class 1) 83%; Recall (Class 1) 55%  

# Dashboard

A Power BI Cancellation Dashboard was created to visualize:

- Total bookings
- Cancellation rate
- Revenue loss
- Repeat guest rate
- Cancellation trends
- Lead time analysis
- Deposit behavior
- Customer segmentation
- Monthly cancellation patterns


# Business Impact

The analysis can help hospitality businesses:

- Reduce cancellation-related revenue loss
- Improve pricing strategies
- Optimize seasonal room pricing
- Design targeted retention campaigns
- Improve demand forecasting

# Author

Devi Smita
Muhammad Zaky Muqoddas
