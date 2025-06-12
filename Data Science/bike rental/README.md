# 🚴‍♀️ AI-Powered system for predicting Urban Bike Rental Demand

## 📌 Problem Statement
The goal of this project is to predict the number of bike rentals based on various environmental and seasonal factors like temperature, humidity, hour, season, and weather. This helps rental companies plan and manage resources efficiently.

---

## 📊 Dataset
- **Source**: https://www.kaggle.com/c/bike-sharing-demand/data?select=train.csv
- **Features Used**:
  - `datetime`, `season`, `holiday`, `workingday`, `weather`, `temp`, `atemp`, `humidity`, `windspeed`, `count` (target)

---

## 🧹 Data Preprocessing
- Converted `datetime` into `day`, `month`, `year`, and `hour`
- Removed unnecessary columns like `casual` and `registered`
- Handled categorical features using `get_dummies()`
- Checked for missing values and outliers
- Plotted heatmap to understand correlations

---

## 🤖 Machine Learning Model
- **Random Forest Regressor** (chosen for better accuracy and feature handling)
- Compared with **Linear Regression**
- **Evaluation Metrics**:
  - R² Score: 0.99 ✅  
  - RMSE: 10.60 ✅  

---

## 📈 Visualizations
- Hour vs Count
- Temperature vs Count
- Weather vs Count
- Heatmap for correlation
- Feature importance plot from Random Forest

---

## 🚀 Deployment
The entire project is deployed on **GitHub** for easy access, sharing, and evaluation. It includes the dataset, Jupyter Notebook, and complete analys

---

## 🙋‍♀️ Author
**Kalyani Kodali**  
Intern @ EDUNET Foundation  
Learning Data Science & AI 💡

---

## 💬 Note
This project was developed as part of a learning internship and focuses on building strong foundational understanding of machine learning, EDA, and model evaluation.
