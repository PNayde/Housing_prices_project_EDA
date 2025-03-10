# 🏡 House Prices - Exploratory Data Analysis (EDA) and Data Preparation

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Ames Housing dataset** to identify key factors that influence house prices. The dataset contains various features about residential homes in Ames, Iowa, and this analysis prepares the data for future predictive modeling (e.g., regression).

The goal is to **understand the target variable `SalePrice`**, explore important predictors, and ensure that the data is clean and ready for machine learning.

---

## ✅ Key Steps Covered in This Project

1. **Dataset Exploration**
   - Overview of the dataset's structure, size, and key variables.
   - Understanding missing data and data types.

2. **Exploration of Target Variable (`SalePrice`)**
   - Univariate analysis (distribution, outliers, skewness, kurtosis).
   - Visualization of the target variable to understand spread and shape.

3. **Outlier Handling**
   - Identifying and capping extreme `SalePrice` values using Winsorization.
   - Ensuring that outliers do not distort the analysis.

4. **Feature Relationships (Bivariate Analysis)**
   - Analyzing how key features like `OverallQual`, `GarageCars`, `GrLivArea`, and `Neighborhood` affect `SalePrice`.
   - Visualizations using bar plots, boxplots, and point plots to uncover relationships.

5. **Categorical Feature Analysis**
   - Exploring important categorical variables such as `KitchenQual` and `Neighborhood`.
   - Understanding how these categories impact house prices.

---

## 📊 Visualizations and Analysis Highlights

- **Distribution plots** for `SalePrice` before and after outlier handling.
- **Bar plots** showing the average `SalePrice` by `Overall Quality`, `Garage Cars`, and `Neighborhood`.
- **Boxplots** to explore price variability within categories.
- **Point plots** for visualizing interactions (e.g., `KitchenAbvGr` and `KitchenQual`).

---

## 📂 Dataset

- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- Files expected:
  - `train.csv`
  - `test.csv`

⚠️ **Note**: To run this notebook, please ensure that these files are in the **same directory** as the notebook or adjust file paths accordingly.

---

## 🚀 How to Use This Notebook

1. Clone or download this repository.
2. Place `train.csv` and `test.csv` in the same directory as the notebook.
3. Open the `Housing_EDA.ipynb` notebook and run the cells sequentially to explore the analysis.

---

## 🔑 Key Takeaways

- **Overall Quality** and **GrLivArea** are among the most important predictors of `SalePrice`.
- Neighborhood plays a crucial role in determining house price, reflecting location value.
- Kitchen Quality is strongly associated with higher sale prices.
- Outliers in `SalePrice` need careful handling to avoid skewing model training.
- Distribution of `SalePrice` is right-skewed and may require log transformation for modeling.

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out:

- GitHub: https://github.com/PNayde
- LinkedIn: https://linkedin.com/in/plamena-naydenova
- Email:  plamena.naydenova@gmail.com


---

**Thank you for reviewing this project!**
