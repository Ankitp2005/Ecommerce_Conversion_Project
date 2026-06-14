# Ecommerce_Conversion_Project
Predicting customer purchase intent using feature engineering, hyperparameter optimization, explainable AI, and a weighted ensemble of LightGBM, XGBoost, CatBoost, and Random Forest models.

# 🛒 E-Commerce Conversion Prediction

Can we predict which visitors are most likely to make a purchase before they leave an online store?

This project tackles that challenge using a powerful ensemble machine learning pipeline built on LightGBM, XGBoost, CatBoost, and Random Forest models. Starting from raw customer behavior, demographic, and session data, I engineered meaningful features, optimized models with Optuna, and combined the strongest performers through a weighted ensemble strategy.

Key highlights:

* 🔍 In-depth exploratory data analysis to uncover conversion patterns
* ⚙️ Advanced feature engineering with 18 custom behavioral and demographic features
* 🚀 Hyperparameter optimization using Optuna and Stratified 5-Fold Cross Validation
* 🎯 Threshold optimization for improved F1-score on imbalanced data
* 🤝 Weighted ensemble learning for stronger predictive performance
* 📊 SHAP-based explainability to understand what drives customer purchases

The final model identifies high-intent customers more accurately than individual models, demonstrating how feature engineering, ensemble learning, and explainable AI can be combined to solve real-world business problems.

**Tech Stack:** Python, Scikit-Learn, LightGBM, XGBoost, CatBoost, Optuna, SHAP, Pandas, NumPy, Matplotlib

⭐ If you find this project interesting, feel free to explore the notebook and contribute ideas for further improvements.
