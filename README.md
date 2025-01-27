# Pandas Data Analysis with Python

This repository contains a Jupyter Notebook demonstrating fundamental **data manipulation and analysis** techniques using the **Pandas** and **NumPy** libraries in Python. The notebook covers essential operations for working with data, handling missing values, sorting, applying functions, and performing exploratory data analysis (EDA).

## Features

### 1. **DataFrame Creation and Basic Operations**
- Creating DataFrames manually.
- Accessing and displaying data using `.head()`, `.tail()`, and column selection.
- Extracting unique values and counting distinct entries using `.unique()` and `.nunique()`.
- Applying functions to DataFrame columns.
- Summing values of columns.
- Sorting values and updating DataFrames with `sort_values()`.

### 2. **Handling Missing Values**
- Checking for missing values using `.isnull()`.
- Removing missing values with `.dropna()`.
- Filling missing values with custom replacements using `.fillna()`.

### 3. **Reading and Writing Data**
- Loading CSV files using `pd.read_csv()`.
- Getting dataset overview with `.info()` and statistical summaries using `.describe()`.
- Extracting insights from specific columns, such as:
  - Calculating the mean and max values.
  - Finding specific employees and their corresponding job titles.
  - Identifying employees with the highest salaries.

### 4. **Data Exploration and Slicing**
- Selecting rows based on conditions using `.loc` and `.iloc`.
- Indexing specific columns and rows.
- Converting DataFrame slices into NumPy arrays.

### 5. **Visualization**
- Using `matplotlib` to visualize basic plots (to be extended).

## Installation

Ensure you have the following libraries installed to run the notebook:

```bash
pip install pandas numpy matplotlib

