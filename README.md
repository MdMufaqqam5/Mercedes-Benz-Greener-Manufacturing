# 🚗 Mercedes-Benz Test Bench Time Reduction Project

## 📌 Overview

This project focuses on reducing the time a Mercedes-Benz vehicle spends on the test bench by leveraging **machine learning techniques**. The objective is to improve testing efficiency while maintaining the highest safety and quality standards expected in the automotive industry.

## 🎯 Problem Statement

Mercedes-Benz vehicles come with a wide range of feature combinations. Each configuration must be tested individually, which significantly increases testing time and operational cost.

The goal of this project is to:

* Predict test bench time for different vehicle configurations
* Optimize the testing process using machine learning
* Reduce overall testing duration without compromising quality

## 📊 Dataset Preprocessing

To ensure high-quality input data for modeling, the following preprocessing steps were performed:

* Removed **zero-variance columns** (no predictive value)
* Handled **missing (null) values** appropriately
* Analyzed and reviewed **unique values** in both training and test datasets
* Ensured consistency between train and test feature distributions

## 🧠 Feature Engineering

* Applied **Label Encoding** to convert categorical variables into numerical format
* Prepared data for compatibility with machine learning models

## 📉 Dimensionality Reduction

* Used **Principal Component Analysis (PCA)** to reduce feature dimensions
* Retained maximum variance while minimizing feature complexity
* Helped improve model efficiency and reduce overfitting

## 🤖 Model Development

* Implemented **XGBoost Regressor** for prediction
* Chosen for its:

  * High performance on structured/tabular data
  * Efficiency and scalability
  * Strong gradient boosting capabilities

## 🔮 Prediction

The trained XGBoost model was used to:

* Predict test bench time for unseen vehicle configurations
* Enable better planning and optimization of testing resources

## ✅ Results & Impact

This project demonstrates how machine learning can significantly:

* Reduce test bench time
* Improve operational efficiency
* Lower emissions through optimized testing cycles
* Maintain strict automotive quality standards

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* XGBoost
* PCA (Dimensionality Reduction)

## 📌 Future Improvements

* Hyperparameter tuning for further performance improvement
* Experiment with deep learning models
* Deploy model using FastAPI or Flask
* Build an interactive dashboard for predictions

## 📄 License

This project is for educational and research purposes.

## 📄 Author

MOHAMMED MUFAQQAM SANJAR GHORI.

