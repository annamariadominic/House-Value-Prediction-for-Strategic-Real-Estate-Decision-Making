# House Value Prediction for Strategic Real Estate Decision-Making

## Overview
This repository contains the project for the course "Data Science For Business – Spring 2024." The project, undertaken by Anna Dominic, Karthikeyan Shanmugam, Manisha Goyal, and Siri Desiraju, focuses on predicting house values to support strategic decision-making in real estate. Due to the sensitive nature of the data, the code and data are not shared publicly.

## Team Members
- Anna Dominic (amd9200@nyu.edu)
- Karthikeyan Shanmugam (ks6964@nyu.edu)
- Manisha Goyal (mg7609@nyu.edu)
- Siri Desiraju (scd4156@nyu.edu)

## Project Structure

### 1. Business Understanding
- **Objective**: Develop a predictive model to estimate residential property prices in Ames, Iowa, based on diverse features, aiding stakeholders in making data-driven decisions.
- **Impact**: Helps real estate agents, developers, homeowners, and buyers in pricing, investment strategies, renovation planning, and market analysis.
- **Target Stakeholders**:
  - Real Estate Agents
  - Real Estate Developers
  - Homeowners
  - Home Buyers

### 2. Data Understanding
- **Data Source**: The dataset is sourced from Kaggle and includes over 1,400 properties in Ames, Iowa, with 79 explanatory variables.
- **Data Features**: Mix of numeric and categorical variables describing physical attributes, quality, age, and more.
- **Potential Bias**: Recognizes subjectivity in quality assessments and possible biases from non-random sampling.
- **Preliminary Observations**: Diverse range of properties catering to a wide demographic.

### 3. Exploratory Data Analysis (EDA)
- **Distribution of Sale Price**: Right-skewed distribution indicating most homes are in the lower to mid-range price segments.
- **Correlations and Relationships**: Strong associations found between sale price and features like overall quality, living area, and garage capacity.
- **Hypothesis Testing**: Validated assumptions about the impact of remodeling and property type on sale prices.

### 4. Data Preparation
- **Cleaning**: Addressed missing values and outliers, preserved meaningful NA values, and removed unresolved missing values.
- **Feature Engineering**: Encoded categorical variables, created new features, and normalized the dataset.
- **Feature Selection**: Used Lasso Regression for feature selection, resulting in a set of 88 significant features.

### 5. Modeling
- **Model Development Strategy**: Utilized diverse models and comprehensive feature analysis with parameter optimization through Grid Search and Cross-Validation.
- **Models**: 
  - Lasso Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Neural Network
  - XGBoost
  - CatBoost
  - Ensemble Methods (Averaging, Stacking)
- **Model Selection**: XGBoost was chosen for its excellent predictive performance with an R² score of 0.918 and an RMSE of $22,326.72.

### 6. Evaluation
- **Evaluating the Model Performance**: Used actual vs. predicted values and residuals plots to confirm the model’s accuracy.
- **Identifying Key Features**: Feature importance and SHAP values analysis identified significant factors affecting house prices, like living area, quality, and location.

### 7. Recommendations and Impact
- **Real Estate Agents**: Accurate pricing and investment returns assessment.
- **Real Estate Developers**: Focus on two-story dwellings, quality living spaces, and garages.
- **Homeowners**: Assess property value and evaluate renovations.
- **Home Buyers**: Evaluate potential homes and budget considerations.

### 8. Extending Scope to Other Cities
- Applied the model to markets like New York, California, and Seattle, showing varied performance and highlighting the need for local data adaptation.

### 9. Future Work
- **Enhancements**: Include local economic indicators, consumer behavior insights, and real-time market data for improved model accuracy.

### 10. Conclusion
The project successfully developed a predictive model using XGBoost, providing valuable insights and recommendations for various real estate stakeholders.

### 11. Appendix
- **Group Contribution**: Equal contributions from all team members.
- **Data Source and Code Repository**:
  - Datasets:
    - [Ames](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
    - [New York](https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market)
    - [California](https://www.kaggle.com/datasets/shibumohapatra/house-price)
    - [Seattle](https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle)
  - Source code: [GitHub Repository](https://github.com/manisha-goyal/housing-value-predictor)

## Contact
For further information, please contact the team members via their provided email addresses.
