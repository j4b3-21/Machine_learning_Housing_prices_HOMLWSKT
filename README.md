# California Housing Price Prediction 🏡

This repository contains my implementation of the **Chapter 2 end-to-end Machine Learning project** from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* by Aurélien Géron.  

The goal of this project is to build an **end-to-end machine learning pipeline** that predicts housing prices in California based on various features such as location, income levels, and population.

---

## 📌 Project Overview
This project demonstrates the **typical workflow of a machine learning project**:
1. **Data Loading & Exploration** – Load the California housing dataset, explore distributions, correlations, and patterns.
2. **Data Visualization** – Plot histograms, scatter plots, and correlation heatmaps to understand the data.
3. **Train-Test Split** – Create a stratified split based on income categories to ensure fair distribution.
4. **Data Preprocessing** – Handle missing values, categorical encoding, feature scaling, and feature engineering (e.g., new ratios).
5. **Model Training** – Train multiple models such as:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
6. **Model Evaluation** – Evaluate models using **RMSE** (Root Mean Squared Error) and perform **cross-validation**.
7. **Hyperparameter Tuning** – Use **GridSearchCV** and **RandomizedSearchCV** to find the best hyperparameters.
8. **Final Model** – Select the best-performing model and evaluate it on the test set.

---

## ⚙️ Tech Stack
- **Language:** Python 3  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Matplotlib & Seaborn  
  - Scikit-learn  

---

### To generate the model and have a .pkl file , run the complete jupter notebook

---

## 🚀 Results
- **Best Model:** Random Forest Regressor 🌲  
- **Performance:** Achieved low RMSE compared to Linear Regression and Decision Tree.  
- Feature engineering (ratios like `rooms_per_household`) significantly improved performance.  

---

## 📖 Learnings
- How to structure a **real ML project** end-to-end.  
- Importance of **data preprocessing & feature engineering**.  
- Why **cross-validation and hyperparameter tuning** are essential.  
- How to use **Scikit-learn pipelines** for clean and reproducible workflows.  

---

## 🔗 Resources
- Book: *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* (Aurélien Géron)  
- Dataset: California Housing Dataset (from Scikit-learn)  

---

## 🤝 Connect with Me
If you’re also working on ML projects, feel free to connect:  
- [LinkedIn](https://www.linkedin.com/in/bhuvan-m-acharya-7b9256335/)
- [GitHub](https://github.com/j4b3-21)  

---

⭐ If you found this helpful, don’t forget to star the repo!

