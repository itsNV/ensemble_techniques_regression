# House Price Prediction using Ensemble Regression Models

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

This project focuses on **predicting house prices** using multiple **ensemble regression techniques**.  
The goal is to compare model performance and evaluate predictions using error metrics and visual analysis.

---

## Dataset
- **Name:** House Price Prediction Dataset
- **Type:** Tabular regression dataset
- **Target Variable:** House Price
- **Features:** Numerical and categorical features related to property characteristics

---

## Models Implemented
- Random Forest Regressor  
- AdaBoost Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

---

## Workflow
1. Initialize the regression model  
2. Fit the model on training data  
3. Predict values for `X_test`  
4. Evaluate performance using **Mean Absolute Error (MAE)**  
5. Visualize errors and predictions using **Matplotlib** and **Seaborn**  

---

## Evaluation & Visualization
- **Metric Used:** Mean Absolute Error (MAE)  
- **Residual Analysis:**  
  - Scatter plot of `y_test` vs `y_pred`  
  - Residual distribution using `sns.displot(y_test - y_pred)`  

These visualizations help in understanding prediction spread, bias, and outliers.

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  

---

## Project Structure
├── house_price_prediction.ipynb

├── README.md

---

## Key Takeaways
- Ensemble regression models handle non-linear relationships effectively
- MAE is a reliable metric for real-world price prediction
- Residual plots help diagnose bias and outliers
- XGBoost and Gradient Boosting generally outperform simpler models

---

## Author
**Nisarg Patel**  
Aspiring Data Scientist | Machine Learning Enthusiast

---

*If you found this project useful, feel free to star the repository!*
