# DAI-101-Assignment-1

### **Project Title:**
DAI Assignment 1 - Ford Car Dataset Analysis

### **Author:**
23112044 - Ishu Raj Gupta

### **Project Overview:**
This project performs an exploratory data analysis (EDA) on the Ford car dataset, analyzing price trends, mileage, engine size, and other key attributes. The analysis includes univariate, multivariate, and outlier detection techniques, along with additional insights into car price trends and feature engineering.

### **DataSet:**
The dataset consists of various attributes of Ford cars, including:
- Numerical Features: year, price, mileage, tax, mpg, engineSize
- Categorical Features: model, transmission, fuelType

### **Workflow:**

#### **Data Cleaning:**
- Handled missing or inconsistent values in the dataset.
- Removed irrelevant columns that don't contribute to the analysis.

#### **Univariate Analysis:**
- Numerical Columns: Distribution plots for price, mileage, tax, etc.
- Categorical Columns: Count plots for model, transmission, and fuelType.

#### **Outlier Detection & Handling:**
- Boxplots to detect extreme values.
- Removal of outliers using Z-score (threshold = 3).

#### **Bivariate Analysis:**
- Correlation Heatmap: Visualizing relationships between numerical variables.
- Pairplots: Exploring feature interactions.
- Boxplots: Showing price & mileage distribution across car categories.

#### **Additional Insights:**
- Price Trends Over the Years 
- Top 10 Most Common Car Models 
- Fuel Type vs. Mileage Distribution 
- Transmission Type vs. Price (Violin Plot) 
- Feature Engineering: Creating Price_per_Litre for better comparisons.

### **Results:**
The project provides detailed visualizations and insights into price trends, car features, and market patterns to assist with decision-making in car pricing and selection.

### **Dependencies:**
- pandas
- numpy
- seaborn
- matplotlib
- scipy
------------------------------------------------------------------------------------------------------------------------------
