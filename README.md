# Employee Data Cleaning Project

## Project Overview

This project demonstrates the process of cleaning a raw employee dataset using Python and Pandas.

The dataset contains common real-world data quality issues such as:

- Missing values
- Duplicate records
- Inconsistent data
- Categorical variables

The objective is to transform the raw dataset into a clean and analysis-ready dataset.

---
## Data Quality Issues

The raw dataset contains:

- Missing values in Age, Salary, Department, and Experience
- Duplicate employee records
- Categorical columns requiring preprocessing

---

## Data Cleaning Steps

### 1. Data Loading

Loaded the dataset using Pandas.

### 2. Missing Value Analysis

Checked missing values using:

```python
df.isnull().sum()
```

### 3. Handling Missing Values

- Age → Filled using Mean
- Salary → Filled using Median/Mean
- Experience → Filled using Mean
- Department → Filled using Mode

### 4. Duplicate Removal

Removed duplicate rows using:

```python
df.drop_duplicates()
```

### 5. Data Validation

Verified:

- No missing values remain
- Dataset is ready for analysis

### 6. Exporting Cleaned Dataset

Saved the cleaned dataset as:

```text
employee_cleaned.csv
```

---

## Technologies Used

- Python
- Pandas
- Jupyter Notebook

---

## Project Structure

```text
employee-data-cleaning/
│
├── emp.csv
├── employee_cleaned.csv
├── Employee.ipynb
├── README.md
```

---

## Learning Outcomes

Through this project, I learned:

- Data preprocessing fundamentals
- Handling missing values
- Working with categorical data
- Exporting cleaned datasets using Pandas

---

## Author

Reshmi S
