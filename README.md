# Data_Analysis_project (pandas)
Got it 👍 Prasad — thanks for clarifying!
Since your notebook mainly focuses on **basic Pandas operations, data cleaning, and filtering**, not full EDA, I’ll update the documentation accordingly (removing “Exploratory Data Analysis” mentions and keeping it focused on **data handling and manipulation**).

Here’s your **revised project documentation** 👇

---

# 📘 **Amazon Prime Titles – Data Analysis Using Pandas**

## **Table of Contents**

1. **Project Overview**
2. **Features**
3. **Concepts Covered**
4. **Installation**
5. **How to Use**
6. **Dataset Source**
7. **Insights Summary**
8. **Future Enhancements**
9. **Author**

---

## **1. Project Overview**

This project demonstrates **basic data analysis operations using Pandas** on the *Amazon Prime Titles Dataset*.
It focuses on performing data loading, inspection, cleaning, and filtering to understand and manipulate tabular data efficiently using Python.

The goal is to gain hands-on experience with fundamental data-handling techniques essential for any data analytics or data science workflow.

---

## **2. Features**

* 📂 **Dataset Loading** – Reads and displays data using Pandas.
* 🧾 **Data Inspection** – Views dataset shape, column names, and data types.
* 🧹 **Data Cleaning** – Handles missing values, trims spaces, and converts date formats.
* 🔍 **Filtering and Indexing** – Extracts subsets of data based on specific conditions (e.g., release year, country).
* ⚙️ **Data Transformation** – Converts duration strings into numeric values for easier processing.

---

## **3. Concepts Covered**

* **Pandas Operations:** `read_csv()`, `head()`, `tail()`, `info()`, `shape`, `columns`
* **Data Cleaning:** Handling missing values with `dropna()`, type conversion with `to_datetime()`
* **Filtering:** Conditional selection using Boolean indexing (`df[df['column'] == value]`)
* **Feature Extraction:** Creating new columns (e.g., numeric duration from string)
* **Basic Analysis:** Viewing subsets and summaries of data

---

## **4. Installation**

Make sure you have Python and required libraries installed.

```bash
pip install pandas numpy
```

You can run the notebook using:

* **Jupyter Notebook**, or
* **VS Code** with the Jupyter extension enabled.

---

## **5. How to Use**

1. Download or clone the project folder.
2. Open the notebook file:

   ```
   b3856ea8-c4b6-41de-a449-168e3732e8c6.ipynb
   ```
3. Place the dataset file `amazon_prime_titles.csv` in the same folder.
4. Run each cell in order to:

   * Load and display dataset
   * Clean data (remove null values, convert columns)
   * Filter data by year, country, or type
   * Transform columns (like duration → minutes)

---

## **6. Dataset Source**

**Dataset:** Amazon Prime Titles
**Source:** [Kaggle – Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
**Description:** Contains detailed information about Amazon Prime Video titles including show ID, title, director, cast, country, release year, rating, and duration.

---

## **7. Insights Summary**

* Some columns such as *cast* and *date_added* had missing values, which were cleaned.
* Majority of the data entries represent **Movies**, with fewer TV Shows.
* The dataset includes movies and shows from various countries, including India and the USA.
* Filtering by release year helped isolate recent titles (e.g., post-2015).
* Converted duration strings (e.g., “90 min”) into numeric form for further use.

---

## **8. Future Enhancements**

* 📊 Add visualization using **Matplotlib/Seaborn** for better understanding.
* 🧠 Include EDA (Exploratory Data Analysis) to discover content trends.
* 🧩 Create dashboards using **Power BI** or **Streamlit**.
* 🕵️ Add summary statistics such as most frequent countries, top release years, etc.

---

## **9. Author**

👤 **Name:** Prasad Goud
🎓 **Role:** Engineering Student 
💻 **Skills Used:** Python, Pandas, NumPy, Data Cleaning, Filtering
📅 **Year:** 2025

---


