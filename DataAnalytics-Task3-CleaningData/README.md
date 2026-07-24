# Task 3: Cleaning Data — Cafe Sales Dataset

## 👤 Author
**Sharvari Gaikwad**
Data Analytics Intern @ Oasis Infobyte

## 🎯 Objective
The goal of this task is to clean a raw, messy retail sales dataset (`dirty_cafe_sales.csv`) and prepare it for accurate analysis by identifying and fixing data quality issues such as missing values, duplicates, inconsistent formatting, and incorrect data types.

## 📊 Dataset
- **File:** `dirty_cafe_sales.csv`
- **Description:** Transaction-level sales data from a cafe, including fields such as item name, quantity, price, transaction date, and payment method.
- **Output:** `cleaned_dirty_cafe_sales.csv` — the cleaned version of the dataset, ready for analysis.

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## 🧹 Cleaning Steps
1. Loaded the raw dataset and performed an initial inspection (shape, data types, null values).
2. Identified and handled missing values in key columns.
3. Removed duplicate records.
4. Standardized inconsistent text formatting (e.g., item names, categories).
5. Corrected data types (e.g., converting date columns to datetime, price/quantity to numeric).
6. Detected and treated outliers/invalid entries.
7. Exported the cleaned dataset as `cleaned_dirty_cafe_sales.csv`.

## 🔑 Key Findings
- The raw dataset contained missing and duplicate records that could have skewed analysis if left untreated.
- Several columns had inconsistent formatting that was standardized for reliable grouping and aggregation.
- After cleaning, the dataset is consistent, duplicate-free, and ready for further exploratory analysis or visualization.

## 📁 Files Included
| File | Description |
|------|-------------|
| `Data_Cleaning_Task3.ipynb` | Jupyter Notebook with the full data cleaning workflow |
| `dirty_cafe_sales.csv` | Original raw dataset |
| `cleaned_dirty_cafe_sales.csv` | Final cleaned dataset |
| `README.md` | Project documentation |

## 🏷 Internship
This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)** — Task 3.
