# 📊 Student Performance Analysis & Prediction

## 📌 Overview
This project analyzes the key factors affecting student academic performance and builds predictive models using linear regression.
The goal is to understand how variables such as study hours, sleep, and attendance influence exam scores.

## 🚀 Key Results
- Improved model performance from **R² = 0.20 → R² = 0.54**
- Achieved **Test R² ≈ 0.59** using train-test split
- Demonstrated that multiple factors significantly improve prediction accuracy

## 🔍 Key Insights
- Students who study more tend to achieve higher exam scores  
- Sleep has a moderate impact on academic performance  
- Attendance is positively related to exam results  
- Combining multiple variables provides better predictive performance  

## 📊 Exploratory Data Analysis (EDA)
The dataset was explored to understand patterns and relationships between variables.

Key steps:
- Examined data structure and summary statistics  
- Analyzed relationships between study habits and performance  
- Visualized trends using scatter plots  

Example:
- Study Hours vs Exam Score shows a positive relationship  
- Sleep Hours also contributes moderately to performance  

## 🤖 Modeling

###  Simple Linear Regression
- Used **Hours Studied** to predict exam score  
- Result: **R² ≈ 0.20** (low explanatory power)

###  Multiple Linear Regression
- Used:
  - Hours Studied  
  - Sleep Hours  
  - Attendance  
- Result: **R² ≈ 0.54**
👉 Shows that multiple factors influence performance


## 🧪 Model Evaluation
The model was evaluated using a **train-test split** approach:

- Training data: 80%  
- Testing data: 20%  

**Test Result:**
- Test R² ≈ 0.59  
👉 Indicates that the model generalizes well and does not overfit

## 🧠 Feature Importance
- Study hours have the strongest impact on exam scores  
- Attendance also plays a significant role  
- Sleep contributes moderately  

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

## 📌 Conclusion
This project demonstrates that student performance is influenced by multiple factors.
While study hours alone provide limited predictive power, combining multiple variables significantly improves model performance.
The use of train-test split confirms that the model is reliable and performs well on unseen data.


## 🚀 Future Improvements
- Apply advanced machine learning models (e.g., Random Forest)  
- Include more features for better prediction  
- Perform feature engineering  
