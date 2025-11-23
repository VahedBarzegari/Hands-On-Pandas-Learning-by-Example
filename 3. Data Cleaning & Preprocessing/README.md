
## 🧹 3️⃣ Data Cleaning & Preprocessing

Real-world datasets are almost never clean.
In this section, we focus on essential techniques for preparing messy data before analysis or modeling.

This section teaches you how to detect, fix, and transform data problems using **pandas** tools that are widely used in data science, research, and industry.

---

## 📌 Subsections Covered

### 3.1 Handling Missing Values

You will learn how to:

* Detect missing values using `isna()` and `notna()`
* Remove missing values using `dropna()`
* Fill missing values using `fillna()`
* Forward-fill and backward-fill (`ffill`, `bfill`)
* Handle missing values in specific columns or rows

---

### 3.2 Removing Duplicates

This subsection covers:

* Detecting duplicate rows with `duplicated()`
* Removing duplicates using `drop_duplicates()`
* Keeping first, last, or removing all duplicates
* Handling duplicates based on subset of columns

---

### 3.3 Renaming Columns

You'll learn how to:

* Rename individual columns
* Rename multiple columns at once
* Use lambda functions to clean column names (lowercase, remove spaces, etc.)
* Rename index labels

---

### 3.4 Changing Data Types

This subsection covers:

* Viewing current data types using `dtypes`
* Converting numeric columns (`astype`, `pd.to_numeric`)
* Converting date columns (`pd.to_datetime`)
* Handling invalid data during conversion using `errors='coerce'`

---

### 3.5 String Operations

You'll work with text data using pandas string methods:

* Cleaning text with `.str.strip()`, `.str.lower()`, `.str.upper()`
* Finding and replacing text with `.str.replace()`
* Extracting patterns using `.str.extract()`
* Checking if text contains patterns using `.str.contains()`
* Splitting and expanding strings into multiple columns

---

## 🎯 Goal of This Section

By the end of this section, you will be able to:
✔ Clean real-world messy datasets
✔ Normalize column names and values
✔ Handle missing and incorrect data safely
✔ Prepare data for further analysis or machine learning

---

## 📁 Suggested File Structure

```
Section_03_Data_Cleaning/
├── 03_01_missing_values.ipynb
├── 03_02_duplicates.ipynb
├── 03_03_renaming_columns.ipynb
├── 03_04_changing_datatypes.ipynb
└── 03_05_string_operations.ipynb
```

