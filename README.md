# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is a part of the Data Analyst Internship - **Task 5: Exploratory Data Analysis (EDA)**.

## 📌 Objective

Perform in-depth exploratory data analysis on the Titanic dataset using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib** to uncover hidden trends, insights, and relationships.

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

---

## 📂 Files Included

- `train.csv` — Titanic dataset
- `EDA_Titanic.ipynb` — Jupyter Notebook with all code and analysis
- `Report_Titanic_EDA.pdf` — PDF report of key findings (exported from notebook)
- `README.md` — This documentation file

---

## 🔍 Key EDA Steps

1. **Data Loading & Cleaning**
   - Loaded Titanic dataset using Pandas
   - Checked for null values and data types

2. **Univariate Analysis**
   - Count plots for categorical variables (Survived, Sex, Pclass)
   - Histograms & boxplots for continuous variables (Age, Fare)

3. **Bivariate Analysis**
   - Survival rate vs. Sex and Pclass
   - Age distribution by survival
   - Correlation heatmap

4. **Skewness Handling**
   - Checked skew using `scipy.stats`
   - Applied log transformation to Fare

5. **Visualization**
   - Used heatmaps, histograms, boxplots, and countplots for visual storytelling

6. **Summary of Findings**
   - Females and 1st-class passengers had higher survival rates
   - Fare distribution was heavily skewed and log-transformed
   - Age and Cabin columns had missing data
   - Correlation observed between Fare and Pclass

---

## 📈 Sample Visuals

> ![Survival by Sex](images/survival_by_sex.png)  
> ![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📚 Interview Prep Q&A

### ❓ What is EDA and why is it important?
EDA is the process of visually and statistically analyzing datasets to discover patterns, anomalies, and relationships. It's crucial for understanding data before modeling.

### ❓ Which plots do you use to check correlation?
Correlation heatmaps and pairplots.

### ❓ How do you handle skewed data?
Using log transformations (`np.log1p()`), square root, or Box-Cox transformations.

### ❓ What are univariate, bivariate, and multivariate analyses?
- **Univariate**: One variable (e.g., histogram of Age)
- **Bivariate**: Two variables (e.g., Survival vs. Sex)
- **Multivariate**: Multiple variables (e.g., Pairplots)

### ❓ How do you detect multicollinearity?
Using correlation matrices and Variance Inflation Factor (VIF).

---

## ✅ How to Run

1. Clone the repo
2. Open `EDA_Titanic.ipynb` in Jupyter Notebook
3. Run all cells
4. Export as PDF using:  
   `File → Export Notebook As → PDF`

---

## 🙌 Acknowledgements

Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---
