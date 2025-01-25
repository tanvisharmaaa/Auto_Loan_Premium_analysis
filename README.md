# Auto Lending and Insurance Analysis Project

This repository contains data analysis, predictive modeling, and business recommendations for auto lending and insurance markets. The goal of this project is to analyze trends, build predictive models, and derive actionable insights for both lenders and insurers.

## Project Structure

- **notebooks/**
  - `AutoLending.ipynb`: Contains analysis of auto loan delinquencies and predictive modeling for lending trends.
  - `EDA_Modeling.ipynb`: Includes exploratory data analysis and modeling for auto insurance premiums and risk categorization.

## Project Overview

### Objectives:
1. Analyze trends in auto lending and insurance using publicly available data.
2. Develop predictive models to:
   - Forecast insurance premiums.
   - Categorize states into risk groups (high, medium, low).
   - Score borrowers' creditworthiness.
3. Provide actionable business recommendations for pricing strategies and risk management.

### Approach:
1. **Data Exploration and Preprocessing**:
   - Conducted exploratory data analysis on auto insurance and lending datasets.
   - Cleaned and standardized state-level data from the NAIC for the years 2017 to 2021.
   - Addressed missing values and outliers, normalized variables, and calculated summary statistics.

2. **Predictive Modeling**:
   - Built regression models (Linear Regression, Random Forest, Gradient Boosting, XGBoost) to predict average insurance premiums by state.
   - Evaluated models using R² and RMSE metrics to select the best-performing model.
   - Developed a classification model to segment states into high, medium, and low-risk categories based on claims frequency and severity.

3. **Auto Lending Analysis**:
   - Analyzed trends in auto loan delinquencies using time series analysis and visualizations.
   - Built a custom credit scoring model incorporating factors like income level, credit score, interest rate, and unemployment rate.
   - Applied clustering (K-Means) to segment borrowers into risk categories.

4. **Recommendations**:
   - Dynamic pricing models based on regional trends for auto insurers.
   - Flexible repayment plans and dynamic risk scoring systems for auto lenders.
   - Integration of telematics data to enhance risk assessment and pricing models.

### Key Insights:
- **Auto Lending**:
  - Significant correlation between delinquency rates and economic factors like unemployment.
  - Credit scoring models built on borrower profiles and macroeconomic indicators.

- **Auto Insurance**:
  - Regional trends reveal significant differences in premiums and claim frequency.
  - Predictive models for premiums achieved high accuracy with Gradient Boosting.

### Recommendations:
- Dynamic pricing models tailored to regional risk.
- Telematics data integration for real-time premium adjustments.
- Flexible repayment plans for borrowers to minimize delinquencies.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/tanvisharmaaa/Auto_Loan_Premium_analysis.git
   cd Auto_Loan_Premium_analysis
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebooks in the `notebooks/` folder to explore the analyses:
   ```bash
   jupyter notebook
   ```

## Requirements

- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter

## Future Work
- Extend the analysis to include real-time economic data.
- Explore advanced machine learning models like deep learning.
- Develop dashboards for real-time risk monitoring.

---

**Author:** Tanvi Sharma  

