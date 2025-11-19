# Data Wrangling – README
### Drew Lesh
### 10/27/25 - 10/28/25

This folder contains all Jupyter notebooks for **Section 2: Data Wrangling** of the IBM Data Analyst Capstone Project. These notebooks cover the essential techniques for identifying issues in raw data, correcting them, and preparing datasets for deeper analysis.

---

## 📁 Contents

Six notebooks are included in this section:

### **1. `FindingDups.ipynb`**

Introduces how to detect duplicate records in a dataset using:

* `duplicated()`
* Identifying duplicate rows
* Understanding the impact of duplicates on analysis

---

### **2. `RemovingDups.ipynb`**

Builds on the previous notebook by demonstrating:

* Removing duplicates using `drop_duplicates()`
* Verifying data integrity after removal
* Saving cleaned datasets

---

### **3. `FindingMissing.ipynb`**

Explains how to identify missing values within a dataset using:

* `isnull()` and `notnull()`
* Summary statistics of missing data
* Locating missing values in specific columns

---

### **4. `ImputeMissing.ipynb`**

Covers strategies for handling missing values, including:

* Mean, median, and mode imputation
* Forward/backward filling
* Replacing missing values with constants
* Understanding when various imputation techniques are appropriate

---

### **5. `Normalizing.ipynb`**

Shows how to scale or normalize data using methods such as:

* Min-max normalization
* Z-score standardization
* Why normalization matters for modeling and comparison

---

### **6. `DataWrangling.ipynb`**

A comprehensive notebook that ties together all the concepts in this section, demonstrating:

* Detecting and resolving duplicates
* Addressing missing data
* Applying normalizations
* Producing a final, cleaned dataset ready for analysis

---

## 🛠 Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy

---
