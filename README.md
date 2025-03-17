# 🏡 House Prices - Exploratory Data Analysis (EDA), Modeling, and Kaggle Submission

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and building a **predictive model** on the **Ames Housing dataset** to identify key factors that influence house prices and create accurate predictions for Kaggle competition submission. The dataset contains various features about residential homes in Ames, Iowa.

The goal is to:
- Understand the target variable `SalePrice`.
- Explore important predictors and their relationships.
- Handle outliers and data quality issues.
- Build and fine-tune a **machine learning model (Random Forest)** to predict house prices.
- Generate a final submission for Kaggle.

---

## ✅ Key Steps Covered in This Project

### 📊 Dataset Exploration
- Overview of the dataset's structure, size, and key variables.
- Understanding missing data and data types.

### 📈 Exploration of Target Variable (`SalePrice`)
- Univariate analysis (distribution, outliers, skewness, kurtosis).
- Visualization of the target variable to understand spread and shape.

### 🚨 Outlier Handling
- Identifying and capping extreme `SalePrice` values using Winsorization.
- Ensuring that outliers do not distort the analysis.

### 🔗 Feature Relationships (Bivariate Analysis)
- Analyzing how key features like `OverallQual`, `GarageCars`, `GrLivArea`, and `Neighborhood` affect `SalePrice`.
- Visualizations using bar plots, boxplots, and point plots to uncover relationships.

### 🏷️ Categorical Feature Analysis
- Exploring important categorical variables such as `KitchenQual` and `Neighborhood`.
- Understanding how these categories impact house prices.

### 🛠️ Feature Engineering
- Creation of new features like `TotalSF` (total square footage), `HouseAge`, and `QualGrLiv` (interaction between quality and living area).

### 🌲 Model Building & Hyperparameter Tuning
- Baseline **Linear Regression** model for initial benchmarking.
- **Random Forest Regressor** for advanced modeling.
- **Hyperparameter tuning** using `RandomizedSearchCV` to optimize Random Forest performance.
- Final model trained on **full training data** for prediction on Kaggle test set.

---

## 📊 Visualizations and Analysis Highlights
- Distribution plots for `SalePrice` before and after outlier handling.
- Bar plots showing the average `SalePrice` by `Overall Quality`, `Garage Cars`, and `Neighborhood`.
- Boxplots to explore price variability within categories.
- Point plots for visualizing feature interactions (e.g., `KitchenAbvGr` and `KitchenQual`).
- Correlation analysis and feature importance analysis to identify key drivers of house prices.

---

## 📂 Dataset

- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- **Files expected**:
  - `train.csv`
  - `test.csv`

⚠️ **Note**: To run this notebook, please ensure that these files are in the **same directory** as the notebook, or adjust file paths accordingly.

---

## 🚀 How to Use This Notebook

1. **Clone or download** this repository.
2. Place `train.csv` and `test.csv` in the **same directory** as the notebook.
3. Open the `Housing_EDA.ipynb` notebook and run the cells **sequentially** to explore, analyze, and model the data.
4. To generate Kaggle submission:
   - Run the model training and prediction cells.
   - Save predictions to `submission.csv`.

---

## 🔑 Key Takeaways

- **Overall Quality** and **GrLivArea** are among the most important predictors of `SalePrice`.
- **Neighborhood** plays a crucial role in determining house price, reflecting location value.
- **Kitchen Quality** is strongly associated with higher sale prices.
- **Feature engineering** (e.g., total square footage and house age) improves model performance.
- **Outliers in SalePrice** need careful handling to avoid skewing model training.
- **Random Forest with tuned hyperparameters** achieved **strong predictive performance** with an R² score of **0.90** on validation set.
- **Final predictions ready for Kaggle submission**.

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out:

- **GitHub**: [https://github.com/PNayde](https://github.com/PNayde)
- **LinkedIn**: [https://linkedin.com/in/plamena-naydenova](https://linkedin.com/in/plamena-naydenova)
- **Email**: plamena.naydenova@gmail.com

---

Thank you for reviewing this project!
