# Spend_DNA
# SpendDNA – Financial Transaction Analysis

## 📌 Project Overview

SpendDNA is a Financial Transaction Analysis project developed using **Python, Pandas, and NumPy**. The project analyzes six months of banking transaction data to understand spending habits, identify vendors, categorize expenses, detect unusual transactions, and generate meaningful financial insights.

This project demonstrates how raw financial transaction data can be transformed into valuable information using data analysis techniques.

---

## 🎯 Objectives

- Clean and preprocess transaction data
- Extract vendor names from transaction descriptions
- Categorize transactions into spending categories
- Analyze monthly spending trends
- Perform time-of-day spending analysis
- Detect unusual transactions using Z-Score analysis
- Identify spending archetypes
- Generate a comprehensive financial report

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- GitHub

---

## ✨ Features

### ✅ Transaction Parser
- Loaded and cleaned the transaction dataset
- Removed duplicate records
- Handled missing values
- Converted date and amount columns into appropriate formats

### ✅ Vendor Extraction
- Extracted vendor names from transaction descriptions
- Created a custom vendor mapping dictionary
- Classified transactions by vendor

### ✅ Category Tagging
Categorized transactions into:
- Food Delivery
- Groceries
- Transport
- E-commerce
- Entertainment
- Utilities
- Investments
- Fuel
- Cafe
- Recharge
- Rent
- Personal Transfer

### ✅ Spending Overview
Calculated:
- Total Credit
- Total Debit
- Net Savings
- Savings Rate
- Top Spending Categories
- Top Vendors

### ✅ Monthly Trend Analysis
- Monthly spending summary
- Category-wise spending trends
- Spending comparison across months

### ✅ Time-of-Day Analysis
- Spending by hour
- Peak spending hours
- Food delivery timing analysis
- Cafe visit analysis

### ✅ Anomaly Detection
- Calculated category-wise Z-Scores
- Identified unusually high-value transactions

### ✅ Spending Archetype Detection
Detected spending behaviors such as:
- Foodie
- Shopaholic
- Investor
- Quick Commerce User
- Late-Night Snacker

---

## 📂 Project Structure

```
SpendDNA/
│
├── SpendDNA.ipynb
├── Data set for DADS June(1).csv
├── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/parinitha672/SpendDNA.git
```

Install the required libraries:

```bash
pip install pandas numpy
```

Open **SpendDNA.ipynb** in **Google Colab** or **Jupyter Notebook** and run all the cells.

---

## 📊 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Vendor Extraction
- Category Classification
- Financial Data Analysis
- Monthly Trend Analysis
- Time-Based Analysis
- Anomaly Detection
- Python Programming
- Pandas
- NumPy

---

## 📈 Future Improvements

- Interactive dashboard for spending visualization
- Automated PDF report generation
- Improved vendor identification
- Advanced financial analytics
- Budget tracking and forecasting

---

## 👩‍💻 Author

**Parinitha**

**Data Science Internship Project**

GitHub: https://github.com/parinitha672

---

## 📜 License

This project is developed for educational and internship purposes only.
