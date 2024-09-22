# HUBBLEMIND

# **Predicting Amazon Stock Price Using Market Data**

![Amazon Stock](https://images.mktw.net/im-16011949?width=700&size=1.4849187935034802&pixel_ratio=1.5) <!-- Optional: You can add a relevant image or logo -->

## 📋 **Project Overview**

This project aims to predict **Amazon's stock price** using various financial and market indicators such as:
- Crude Oil Price
- Bitcoin Price
- Nasdaq 100 Index
- S&P 500 Index
- And many more...

By analyzing historical data and applying machine learning models, we provide insights into the relationships between these indicators and Amazon's stock price.

---

## ⚙️ **Technologies Used**
- **Python**: Data manipulation and model development.
- **Pandas**: Data cleaning and preprocessing.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **scikit-learn**: Machine learning model development and evaluation.
- **Jupyter Notebook**: For code execution and documentation.

---

## 📊 **Key Features**
- **Data Preprocessing**: Handling missing values and standardizing features.
- **Exploratory Data Analysis (EDA)**: Visualizing distributions and feature correlations.
- **Model Development**: Linear regression to predict Amazon prices.
- **Cross-Validation**: 5-fold cross-validation for better model performance assessment.
- **Feature Importance**: Analysis of key features affecting Amazon's price.

---

## 🚀 **Project Workflow**

### **Data Exploration & Preprocessing**
- Load and explore the dataset.
- Handle missing values and standardize data.
- Visualize key relationships between features.

### **Model Development**
- Split the data into training and testing sets.
- Train a **Linear Regression** model on the training data.
- Evaluate the model using **MAE**, **MSE**, and **RMSE**.

### **Model Validation & Testing**
- Apply **5-fold cross-validation** to assess model performance.
- Test the model on recent unseen data.
- Analyze feature importance using linear regression coefficients.

### **Documentation & Submission**
- Compile all code and explanations into a Jupyter Notebook.
- Upload the notebook to GitHub along with this README.

---

## 📈 **Results**

- **RMSE on Test Data**: *7.584481133349242*  
- **Cross-Validation Mean Score**: *29.505778768485264*
- **Top Features**:
  1. Nasdaq 100 Price
  2. Crude Oil Price
  3. S&P 500 Price
