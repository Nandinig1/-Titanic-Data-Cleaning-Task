# Task 1: Data Cleaning and Preprocessing - Titanic Dataset

## 📌 Objective:
This task focuses on preparing the Titanic dataset for machine learning by carefully handling missing data, encoding categorical features, scaling numerical columns, and managing outliers to improve data quality.

---

## ✅ Steps Performed:
1. **Dataset Imported:** Loaded the Titanic dataset directly from an online source using Pandas.
2. **Data Inspection:** Reviewed dataset structure and identified missing values.
3. **Missing Data Management:**
   - Replaced missing 'Age' values with the column’s average.
   - Filled empty 'Embarked' entries with the most common port.
   - Dropped the 'Cabin' column due to a high number of missing entries.
4. **Categorical Feature Handling:**
   - Applied one-hot encoding to the 'Sex' and 'Embarked' columns.
   - Removed non-essential columns: 'Name', 'Ticket', and 'PassengerId'.
5. **Feature Scaling:**
   - Used standardization to scale numerical features like 'Age', 'Fare', 'SibSp', and 'Parch'.
6. **Outlier Detection and Removal:**
   - Detected outliers through boxplots.
   - Removed extreme outliers from the 'Fare' column using the IQR technique.
7. **Dataset Exported:**
   - Saved the final cleaned dataset for further analysis or machine learning.

---

## 🛠️ Tools & Libraries Used:
- Google Colab (Python Notebook)
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Files Included:
- `Titanic_Data_Cleaning.ipynb` (Notebook file with all steps)
- `final_titanic_cleaned.csv` (Cleaned dataset)
- `README.md` (This file)

---

## 🚀 Instructions to Run:
1. Open the notebook file in Google Colab.
2. Run each code cell step-by-step.
3. The cleaned dataset will be generated and available for download.

---

## 🔗 Dataset Source:
[Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
