# Retail Monthly Sales Prediction & Business Analysis

## 📌 About the Project

Retail businesses need to understand what factors are affecting their sales so they can make better decisions about inventory, staffing, marketing, and promotions.

In this project, I analyzed retail sales data to understand the factors that influence monthly sales and then built machine learning models to predict monthly sales based on the available business information.

The project follows a complete data analysis process — starting from raw data cleaning, moving through exploratory data analysis and feature engineering, and finally building and evaluating predictive models.

---

## 🎯 What Was the Goal?

The main goal of this project was to answer two questions:

1. **What factors are related to monthly retail sales?**
2. **Can we use these factors to predict monthly sales?**

To answer these questions, I analyzed variables such as:

- Customer footfall
- Advertising spend
- Promotions
- Store type
- Product category
- Seasonal factors
- Monthly sales

---

## 📊 Understanding the Data

The original dataset contained **1,717 retail records**.

Before starting the analysis, I checked the data to understand its structure, data types, missing values, duplicate records, and categorical variables.

During this process, I found **17 duplicate records**, which were removed.

After cleaning, the final dataset contained **1,700 records** for analysis.

---

## 🧹 How Did I Clean the Data?

Real-world data is rarely perfect, so the first step was to make the dataset reliable for analysis.

I:

- Checked for missing values.
- Handled missing numerical values using appropriate statistical imputation.
- Handled missing categorical values.
- Identified and removed duplicate records.
- Checked categorical values for inconsistencies.
- Removed columns that were not useful for the analysis.
- Prepared the cleaned data for further analysis.

This ensured that the analysis and machine learning models were working with consistent and usable data.

---

## 🔍 How Did I Analyze the Data?

After cleaning the data, I performed **Exploratory Data Analysis (EDA)** to understand what was happening in the dataset.

I used visualizations and statistical analysis to investigate relationships between monthly sales and factors such as:

- Customer footfall
- Advertising spend
- Promotions
- Store type
- Product category
- Seasonal factors

I used charts such as distribution plots, scatter plots, and correlation heatmaps to identify patterns and relationships in the data.

This helped me understand which variables appeared to have stronger relationships with monthly sales before building the predictive models.

---

## ⚙️ Preparing the Data for Machine Learning

After completing the exploratory analysis, I prepared the data for machine learning.

The main steps included:

- Separating the target variable from the other features.
- Converting categorical information into numerical values using **one-hot encoding**.
- Preparing numerical features for modeling.
- Investigating skewed variables and applying transformations where appropriate.
- Splitting the data into training and testing sets.

The target variable for the project was:

**Monthly Sales**

---

## 🤖 Building the Prediction Models

I wanted to compare different regression approaches rather than relying on a single model.

Therefore, I built three models:

### 1. Linear Regression

Used as the main baseline model for predicting monthly sales.

### 2. Ridge Regression

Used to test whether regularization could improve the model's performance.

### 3. Lasso Regression

Used to test another regularization approach and understand whether it could improve prediction performance.

---

## 📈 How Did I Measure the Models?

To determine which model performed best, I compared their predictions with the actual sales values.

I used three evaluation metrics:

**MAE (Mean Absolute Error)**  
Shows the average size of the prediction error.

**RMSE (Root Mean Squared Error)**  
Shows prediction error while giving more importance to larger errors.

**R² Score**  
Shows how much of the variation in monthly sales is explained by the model.

---

## 🏆 What Did I Achieve?

After comparing the models, **Linear Regression performed best among the evaluated models**.

The final model achieved:

| Metric | Result |
|---|---:|
| MAE | **0.872 lakhs** |
| RMSE | **1.128 lakhs** |
| R² Score | **71.5%** |

An **R² score of 71.5%** means that the model was able to explain approximately 71.5% of the variation in monthly sales within the evaluated dataset.

The MAE of **0.872 lakhs** means that the model's average absolute prediction error was approximately **₹87,200**.

---

## 💡 What Did I Learn From the Project?

This project helped me understand that building a useful data science solution is not only about creating a machine learning model.

A large part of the work involved:

**Cleaning the data → Understanding the data → Finding patterns → Preparing the data → Building models → Comparing results → Understanding the business meaning**

The analysis showed how factors such as customer activity, advertising, promotions, store characteristics, product categories, and seasonal factors can be investigated to better understand retail sales.

---

## 💼 How Can This Help a Retail Business?

The analysis and predictions can potentially support business decisions such as:

### 📦 Inventory Planning
Sales estimates can help businesses plan inventory and reduce the possibility of overstocking or shortages.

### 👥 Staff Planning
Understanding customer activity and expected sales can help businesses plan staffing requirements.

### 📢 Marketing Decisions
Businesses can analyze the relationship between advertising, promotions, and sales to make better marketing decisions.

### 📊 Sales Planning
Predicted sales can provide an additional data point for setting sales expectations and planning future activities.

---

## 🛠️ Tools & Technologies

**Python**  
Used as the main programming language.

**Pandas & NumPy**  
Used for data cleaning, manipulation, and analysis.

**Matplotlib & Seaborn**  
Used to visualize patterns and relationships in the data.

**Scikit-learn**  
Used to build and evaluate the machine learning models.

**Jupyter Notebook**  
Used to perform and document the complete analysis.

---

## 📌 Final Takeaway

This project demonstrates an end-to-end approach to solving a business problem using data.

I started with raw retail data, cleaned and explored it, identified important patterns, prepared the data for machine learning, built multiple prediction models, compared their performance, and finally translated the results into potential business applications.

The final Linear Regression model achieved an **R² score of 71.5%**, demonstrating that the available business variables could explain a substantial portion of the variation in monthly retail sales.

---

## 👤 About Me

**Divesh Shukla**  
Aspiring Data Analyst

Interested in using **Python, SQL, Excel, Power BI, and data analytics** to solve real-world business problems and turn data into actionable insights.
