# 🏠 House Price Prediction – Internship Project

## 📌 Objective
The goal of this project is to clean, preprocess, and analyze housing data to build a simple model that predicts house prices. This fulfills Task 1 (Data Cleaning) and optionally Task 2 (Visualization & Storytelling) for the Data Analyst Internship.

---

## 📂 Dataset
- Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Dataset used: `train.csv`

---

## 🧹 Task 1: Data Cleaning and Preprocessing

### ✔️ Steps Performed:
- Loaded dataset and explored structure
- Removed duplicates (if any)
- Handled missing values using:
  - Mean/median imputation for numerical fields (e.g., `LotFrontage`)
  - Mode/frequent value for categorical fields (e.g., `Electrical`)
- Standardized column names to lowercase and replaced spaces with underscores
- Converted `YearBuilt`, `GarageYrBlt`, and `MSSubClass` to appropriate datatypes
- Verified and corrected all data types
- Exported cleaned dataset as `cleaned_data.csv`

---

## 📊 Task 2: Data Visualization and Storytelling (Optional)

### Visuals Created:
- Distribution plot of `SalePrice`
- Correlation heatmap of top numerical features
- Scatter plot of `GrLivArea` vs. `SalePrice`
- Boxplot of `OverallQual` vs. `SalePrice`
- Bar chart: Average house prices by neighborhood

### Key Insights:
- `OverallQual`, `GrLivArea`, and `GarageCars` strongly correlate with house prices
- Certain neighborhoods consistently show higher average prices
- There are some outliers where large houses were sold for low prices (possible renovation needs)

---

## 🤖 Model (Optional Bonus)
- Model used: **Linear Regression**
- Features selected: `GrLivArea`, `OverallQual`, `GarageCars`, etc.
- Evaluation Metric: R² Score
- Model performance: ~85–90% accuracy (basic baseline)

---

## 💻 Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (for prediction)

---

## 📁 Files in Repo
- `house_price_prediction.ipynb` – Full notebook (cleaning + EDA + model)
- `train.csv` – Raw dataset (or link to source)
- `cleaned_data.csv` – Cleaned output
- `README.md` – This file
- `screenshots/` – Optional: Visuals from EDA
- `summary.pdf` – Optional: Visual storytelling report

---

## 📝 Submission
This project is submitted as part of the **Data Analyst Internship**:
- ✅ Task 1 – Data Cleaning
- ✅ Task 2 – Visualization & Storytelling *(if visuals included)*

---
