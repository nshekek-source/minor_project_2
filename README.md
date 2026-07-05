# 💰 SpendDNA – Smart Bank Transaction Analyzer

SpendDNA is a Python-based financial analytics project that automatically cleans, categorizes, and analyzes bank transaction data to generate meaningful spending insights.

The project processes raw transaction records, identifies vendors, classifies expenses, detects unusual transactions, and generates a comprehensive financial summary.

---

## 🚀 Features

### 1. Transaction Parser
- Loads bank transaction dataset
- Cleans currency values
- Removes duplicate records
- Standardizes transaction types (Credit/Debit)

### 2. Vendor Extraction
Automatically identifies merchants from transaction descriptions.

Examples:
- Swiggy
- Zomato
- Amazon
- Uber
- Blinkit
- Starbucks
- BookMyShow
- Indian Oil

Unknown vendors are marked as:

```
Uncategorised
```

---

### 3. Expense Category Tagging

Maps vendors into categories such as:

- 🍔 Food Delivery
- ⚡ Quick Commerce
- 🛒 Groceries
- ☕ Cafe
- 🍽 Restaurants
- 🛍 E-commerce
- 🚕 Transport
- ⛽ Fuel
- 🎬 Entertainment
- 💡 Utilities
- 📈 Investments
- 💰 Income
- 🏠 Rent
- 💸 Cash Withdrawal
- 👥 Personal Transfer

---

### 4. Spending Overview

Calculates:

- Total Credits
- Total Debits
- Net Savings
- Savings Rate
- Total Transactions
- Number of Unique Vendors
- Top Spending Categories
- Top Vendors

---

### 5. Monthly Trend Analysis

Analyzes transaction dates to identify monthly spending patterns.

---

### 6. Time-of-Day Analysis

Finds:

- Peak spending hour
- Late-night transactions
- Late-night food orders
- Hourly spending distribution

---

### 7. Anomaly Detection

Uses Z-Score analysis to detect unusual spending.

Outputs:

- Suspicious transactions
- High-value outliers
- Category-wise anomalies

---

### 8. Spending Archetype Detection

Creates a financial personality based on spending habits.

Possible archetypes include:

- 🍔 The Foodie
- ☕ The Cafe Lover
- 🛍 The Shopaholic
- 🚕 The Traveller
- 📈 The Investor
- 🌙 The Late Night Snacker
- 💸 The YOLO Spender
- 🎬 The Entertainer

---

## 📂 Project Structure

```
SpendDNA/
│
├── minor_project_2.ipynb
├── minor_project_2.py
├── Data_set_for_DADS_June.csv
└── README.md
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Google Colab

---

## 📊 Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Vendor Extraction
   │
   ▼
Category Tagging
   │
   ▼
Financial Analysis
   │
   ▼
Time Analysis
   │
   ▼
Anomaly Detection
   │
   ▼
Spending Archetypes
   │
   ▼
Final SpendDNA Report
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/SpendDNA.git
```

2. Install dependencies.

```bash
pip install pandas numpy
```

3. Place the dataset (`Data_set_for_DADS_June.csv`) in the project folder.

4. Run the notebook or Python script.

```bash
python minor_project_2.py
```

---

## 📈 Sample Outputs

The project generates:

- Financial Summary
- Savings Report
- Top Spending Categories
- Vendor-wise Analysis
- Monthly Trends
- Time-of-Day Spending
- Anomaly Report
- Spending Personality

---

## 🎯 Applications

- Personal Finance Management
- Budget Tracking
- Expense Monitoring
- Fraud Detection
- Financial Behaviour Analysis
- Banking Analytics

---

## 👨‍💻 Author

**Navin**  
B.Tech CSE (Data Science)  
SRM Institute of Science and Technology

---

## 📄 License

This project is developed for academic and educational purposes.
