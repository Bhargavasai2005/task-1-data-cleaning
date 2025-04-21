# Task 1 - Data Cleaning and Preprocessing

### 👨‍💻 Internship Task for Data Analyst Role

**Dataset Used:** Mall Customer Segmentation  
**Tools Used:** Python, Pandas, Google Colab

---

## 🧹 Cleaning Steps Performed

- Checked for missing values using `.isnull().sum()`
- No null values found, so no need for `fillna()` or `dropna()`
- Removed duplicate records using `.drop_duplicates()`
- Renamed column headers to be lowercase and replaced spaces with underscores
- Standardized column names for consistency
- Data types were already clean (no date or gender fields needed formatting)

---

## 📁 Files Included

- `Mall_Customers.csv` – Original dataset
- `cleaned_mall_customers.csv` – Cleaned output dataset
- `task1_cleaning.ipynb` – Jupyter/Colab notebook with code
