# Factors Impacting COVID-19 Vaccine Adoption Across U.S. States

Final Group Poster – 36-600: Statistical Learning & Modeling
Carnegie Mellon University

# Project Overview

This project investigates whether COVID-19 vaccine acceptance rates can be predicted at the U.S. state level using demographic, behavioral, and survey-based indicators. The primary research question guiding this work was:

# Can we accurately predict vaccine acceptance rates across U.S. states using statistical and machine learning models?

# Data Source

The dataset was obtained from the CMU Delphi COVIDcast API, which aggregates large-scale survey and public health data related to COVID-19 trends in the United States.

-> Source: https://delphi.cmu.edu/covidcast/

-> Snapshot date: January 10, 2026

# Data Preprocessing & Exploratory Analysis

All analyses were conducted using R. The workflow included:

-> Cleaning and preprocessing the raw data

-> Handling missing and incomplete observations

-> Exploratory Data Analysis (EDA) to understand variable distributions, correlations, and state-level trends

-> Feature preparation for downstream modeling

# Modeling Approach

Multiple supervised learning methods were evaluated to compare predictive performance:

-> Logistic Regression

-> Random Forest

-> k-Nearest Neighbors (KNN)

-> Support Vector Machine (SVM)

-> Decision Tree

-> XGBoost

Models were trained and evaluated using appropriate performance metrics, with a focus on classification accuracy and robustness.

# Results

Among all models tested, the Random Forest classifier demonstrated the strongest performance:

-> Achieved the highest AUC score

-> Exhibited a lower misclassification rate compared to other approaches

-> Provided improved stability across states with varying vaccine acceptance levels

# Key Takeaways

-> Machine learning models can effectively capture state-level patterns in vaccine acceptance

-> Ensemble methods, particularly Random Forest, performed best for this task

-> Public health survey data combined with statistical learning can support data-driven insights into vaccination behavior

# Tools & Skills
-> Programming Language: R

-> Techniques: Data preprocessing, EDA, supervised machine learning, model evaluation

-> Domain: Public health analytics, statistical learning

Domain: Public health analytics, statistical learning
