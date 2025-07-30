# 🧹 Data Cleaning and Exploration – DA-02

This repository contains a Jupyter Notebook (`DA-02.ipynb`) that focuses on **data cleaning** and **basic querying** using Python. The dataset is pre-loaded and analyzed step-by-step using industry-standard tools like **Pandas** and **NumPy**.

---

## 📌 Project Overview

The project is structured in **two main stages**:

### 1. 🔧 Data Cleaning

To prepare the dataset for meaningful analysis, the following cleaning steps were performed:

- **Missing Values in `Description` column:**
  - Only **1,454 missing values** were found.
  - Since this is a relatively small number, the corresponding rows were **removed** from the dataset.
  
- **Missing Values in `CustomerID` column:**
  - A large number of records (**153,080**) had missing values in this column.
  - Removing or guessing them was not reasonable, so these missing values were **replaced with the string `'unknown'`** instead of being deleted.

This ensured data consistency while minimizing unnecessary data loss.

### 2. 🔍 Data Querying

After cleaning, several **queries** were performed to explore the dataset and extract specific insights. These include:

- Searching for products with specific descriptions
- Filtering based on price and quantity
- Identifying potentially free or promotional items
- Investigating seasonal or monthly purchase patterns

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas`
  - `numpy`

---

## 🚀 How to Run

To run the notebook on your local machine:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
