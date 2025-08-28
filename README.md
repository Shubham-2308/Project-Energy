# ⚡ Energy Consumption Prediction using XGBoost

This project applies machine learning—specifically the XGBoost algorithm—to model and predict energy consumption patterns based on various environmental or sensor features. The goal is to support smarter energy usage and planning decisions.

---

## 📌 Project Summary

The notebook:
- Loads and prepares an energy dataset
- Performs data cleaning and feature engineering
- Applies XGBoost Regression for prediction
- Evaluates model performance using RMSE and R²
- Visualizes results to understand model accuracy and insights

---

## 📊 Technologies & Tools Used

- **Language**: Python 3.x
- **Notebook**: Jupyter
- **Libraries**:
  - `pandas` and `numpy` – data handling
  - `matplotlib` and `seaborn` – visualizations
  - `xgboost` – machine learning model
  - `sklearn` – preprocessing and model evaluation

---

## 🧪 Steps Followed

1. **Importing Libraries**  
   Loaded necessary packages for data handling, modeling, and plotting.
2. **Loading Data**  
   Read the dataset from CSV or other sources.
3. **Preprocessing**  
   - Checked for missing values  
   - Performed feature scaling and encoding  
   - Handled outliers (if any)
4. **Feature Engineering**  
   Created new features or selected important ones for training.
5. **Modeling using XGBoost**  
   - Trained a regression model  
   - Tuned hyperparameters (if included)
6. **Evaluation**  
   Evaluated performance using:
   - RMSE (Root Mean Squared Error)  
   - R² Score (Goodness of Fit)
7. **Visualization**  
   - Plotted actual vs predicted values  
   - Visualized feature importance
