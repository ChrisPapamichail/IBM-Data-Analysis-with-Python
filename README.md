# Housing Price Prediction - King County, USA
### IBM Data Science Portfolio Project

An end-to-end data analytics and machine learning project focused on predicting housing prices in King County, Washington (including Seattle). This project was developed as part of the **IBM Data Analysis with Python** professional certification.

## 📊 Project Overview
The objective of this project is to analyze a comprehensive real estate dataset and build predictive models to estimate house market values based on key architectural and geographical features (such as square footage, number of bedrooms/bathrooms, view, grade, and location).

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn

## 🔄 Core Workflow & Methodology

### 1. Data Wrangling & Cleaning
- Handled missing data points using statistical imputation (replacing missing values in key columns with the mean).
- Adjusted data structures and optimized variable data types for modeling.

### 2. Exploratory Data Analysis (EDA)
- Conducted advanced correlation analysis to extract impactful features affecting house valuations.
- Developed categorical visualizations (e.g., box plots evaluating price distributions for waterfront vs. non-waterfront properties).
- Utilized statistical grouping (`groupby`) to analyze regional price segments.

### 3. Model Development & Evaluation
Developed, fine-tuned, and cross-validated multiple regression models to evaluate performance tradeoffs:
- **Simple Linear Regression** as a baseline model.
- **Multiple Linear Regression** using highly correlated features to capture multidimensional patterns.
- **Polynomial Transformations (2nd order)** to extract and learn non-linear relationships.
- **Ridge Regression (L2 Regularization)** optimized with hyperparameter tuning (`Alpha`) to constraint coefficients, manage model complexity, and effectively mitigate overfitting.
- **Scikit-Learn Pipelines** deployed to bundle preprocessing steps (such as data scaling/standardization) and model fitting into a unified, clean object.

## 📈 Key Findings & Performance Summary
- Strong correlations were identified between a house's living area square footage (`sqft_living`), overall building grade, and its final market price.
- Implementing regularization methods and advanced feature scaling significantly enhanced the model's capacity to generalize well on unseen test data.

---
*Note: This project serves as a practical demonstration of regression analysis, feature engineering, and statistical modeling in real-world business scenarios.*
