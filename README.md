# LogS Prediction using Machine Learning (Regression)

This project predicts **Experimental LogS (Solubility)** using Machine Learning regression models.
The models are trained and tested using **Linear Regression** and **Random Forest Regression**.

The project also includes evaluation metrics, cross validation, hyperparameter tuning, and complete visualization graphs.

---

## 📌 Project Objective
To build a regression model that can predict the **LogS (log solubility)** value based on molecular/chemical features.

---

## 🧠 Models Used
- Linear Regression
- Random Forest Regressor (with GridSearchCV tuning)

---

## ⚙️ Features of the Project
✅ Train/Test split  
✅ Model performance evaluation (MSE, R²)  
✅ Cross Validation  
✅ Hyperparameter Tuning using GridSearchCV  
✅ Model saving using Joblib  
✅ Feature Importance visualization  
✅ Complete regression graphs (Residual plots, histograms, boxplots etc.)

---

## 📊 Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)

---

## 📈 Visualizations Included
- Actual vs Predicted (Train & Test)
- Residual Plot (Train & Test)
- Residual Histogram (Train & Test)
- Absolute Error Plot
- Boxplot of Residuals
- Feature Importance Plot (Random Forest)

---

## 🏆 Best Model
Random Forest Regression performed best after tuning:

- `n_estimators = 200`
- `max_depth = None`

---

## 💾 Saved Model
The trained model is saved as:
