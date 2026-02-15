# 🏡 California Housing Price Predictor

## 📌 Project Overview
An end-to-end Machine Learning project designed to predict housing prices in California based on various demographic and geographical features. The project focuses on data preprocessing, handling outliers, and applying mathematical transformations to improve model accuracy.

## 🚀 Key Features & Workflow
- **Data Cleaning:** Aggressively handled capped outliers in target variables and features (e.g., maximum house age and extreme room counts).
- **Feature Engineering:** Created new impactful features like `Income_Per_Person`, `Bedroom_Ratio`, and `Rooms_Per_Person`.
- **Data Transformation:** Applied Log Transformation (`np.log1p`) to the target variable to normalize the distribution.
- **Modeling:** Built and compared **Linear Regression** and **Ridge Regression (with Polynomial Features)** to prevent overfitting.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib/Seaborn

## 📊 Results
By applying robust feature engineering and Polynomial features (degree=2) with Ridge regularization, the model achieved an **$R^2$ Score of 74.5%**, significantly outperforming the baseline linear model.

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/California-Housing-Price-Predictor.git](https://github.com/yourusername/California-Housing-Price-Predictor.git)
