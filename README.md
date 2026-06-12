# 🏦 Banking Transaction Analytics Using SQL

## 📌 Project Overview

This SQL project analyzes banking transaction data to uncover customer behavior, transaction trends, beneficiary performance, and fraud patterns. The project demonstrates the use of SQL for real-world banking analytics and business intelligence reporting.

---

## 🎯 Project Objectives

- Analyze customer transaction behavior
- Identify high-value customers
- Track monthly transaction trends
- Compare transaction types and their contribution
- Detect fraudulent transactions
- Analyze beneficiary performance
- Generate actionable business insights using SQL

---

## 🗄️ Database Schema

The database consists of five tables:

### Customers
Stores customer information.

### Accounts
Contains account details linked to customers.

### Beneficiaries
Stores beneficiary information for transfers and payments.

### Transaction_Types
Contains transaction categories:
- Deposit
- Withdrawal
- Transfer
- Payment

### Transactions
Stores transaction records including:
- Transaction Amount
- Transaction Date
- Account ID
- Beneficiary ID
- Transaction Type
- Fraud Status

---

## 📊 Dataset Summary

| Metric | Value |
|----------|----------|
| Total Customers | 200 |
| Total Accounts | 200 |
| Total Transactions | 5,000 |
| Average Transaction Size | ₹25,207.03 |
| Largest Transaction | ₹49,989.42 |
| Total Fraud Transactions | 44 |
| Fraud Percentage | 0.88% |
| Total Fraud Amount | ₹1,169,783.48 |

---

# 📈 Customer Analytics

## 🏆 Highest Transaction Value Customer

| Customer ID | Total Amount |
|------------|-------------|
| 98 | ₹1,044,437.26 |

Customer **98** generated the highest total transaction value across all customers.

---

## 🔥 Most Active Customer

| Customer ID | Transaction Count |
|------------|------------------|
| 98 | 40 |

Customer **98** also performed the highest number of transactions.

---

## 🌍 City-wise Top Customers

| City | Customer ID |
|---------|---------|
| Bangalore | 152 |
| Delhi | 98 |
| Mumbai | 63 |
| Pune | 31 |

These customers generated the highest transaction value in their respective cities.

---

# 💳 Transaction Analytics

## Transaction Volume Overview

| Metric | Value |
|---------|---------|
| Total Transactions | 5,000 |
| Average Transaction Size | ₹25,207.03 |
| Largest Transaction | ₹49,989.42 |

---

## Monthly Transaction Trends

| Month | Transactions |
|---------|------------|
| April 2025 | 437 |
| August 2025 | 458 |

Transaction activity varies throughout the year, with August recording one of the highest transaction volumes.

---

## Transaction Type Distribution

| Transaction Type | Count |
|------------------|-------|
| Withdrawal | 1,289 |
| Deposit | 1,249 |
| Transfer | 1,244 |
| Payment | 1,218 |

### Key Findings

✅ Withdrawal is the most common transaction type.

✅ Payment is the least common transaction type.

✅ Withdrawal transactions generated the highest total transaction amount.

---

# 👥 Beneficiary Analytics

## Top Beneficiary by Amount

| Beneficiary ID |
|---------------|
| 27 |

Beneficiary **27** received the highest cumulative transaction amount among all beneficiaries.

---

# 🚨 Fraud Analytics

## Fraud Overview

| Metric | Value |
|---------|---------|
| Total Fraud Transactions | 44 |
| Fraud Percentage | 0.88% |
| Total Fraud Amount | ₹1,169,783.48 |

---

## Monthly Fraud Count

| Month | Fraud Count |
|---------|------------|
| January | 3 |
| April | 4 |
| June | 4 |
| July | 4 |
| August | 6 |
| November | 6 |

August and November recorded the highest number of fraudulent transactions.

---

## Highest Fraud Amount Month

| Month | Fraud Amount |
|---------|-------------|
| April | ₹98,757.54 |

April recorded the highest fraud loss amount.

---

## Fraud by Transaction Type

### Fraud Count

| Transaction Type | Fraud Count |
|------------------|------------|
| Deposit | 13 |
| Payment | 12 |
| Transfer | 11 |
| Withdrawal | 8 |

### Fraud Amount

| Transaction Type | Fraud Amount |
|------------------|-------------|
| Transfer | ₹366,177.65 |

Although Deposit transactions had the highest fraud count, Transfer transactions generated the highest fraud loss amount.

---

## Top Fraud Accounts

| Account ID | Fraud Count | Fraud Amount |
|------------|------------|-------------|
| 116 | 3 | ₹75,647.47 |
| 3 | 1 | ₹25,962.64 |
| 8 | 1 | ₹2,132.10 |

Account **116** recorded the highest fraud amount and fraud frequency.

---

# 🛠️ SQL Concepts Used

- SELECT Statements
- Aggregate Functions
- GROUP BY
- ORDER BY
- CASE Statements
- Common Table Expressions (CTEs)
- Window Functions
- INNER JOIN
- LEFT JOIN
- Subqueries
- Date Functions
- Ranking Functions
- Fraud Detection Queries

---

# 📋 Business Questions Solved

### Customer Analysis
- Who are the highest-value customers?
- Which customers perform the most transactions?
- Which customers dominate transactions in each city?

### Transaction Analysis
- Which transaction type is most common?
- Which transaction type generates the highest amount?
- What are the monthly transaction trends?
- What is the average transaction size?

### Beneficiary Analysis
- Which beneficiary receives the highest amount?
- Who are the top beneficiaries by transaction volume?

### Fraud Analysis
- What percentage of transactions are fraudulent?
- Which month has the highest fraud count?
- Which month has the highest fraud amount?
- Which transaction types are most vulnerable to fraud?
- Which accounts are involved in the most fraud?

---

# 💡 Business Recommendations

### Customer Retention
Develop loyalty and premium banking programs for high-value customers such as Customer 98.

### Fraud Prevention
Implement enhanced monitoring for Transfer transactions, as they contribute the highest fraud losses.

### Risk Management
Strengthen verification procedures for Deposit and Payment transactions due to their higher fraud occurrence rates.

### Beneficiary Monitoring
Regularly review high-volume beneficiaries, especially Beneficiary 27, for unusual transaction activity.

### Transaction Optimization
Analyze Withdrawal transactions to understand customer cash usage patterns and improve banking services.

---

# 🚀 Tools Used

- SQL
- MySQL
- Excel
- GitHub

---

## 👨‍💻 Author

**Shivranjani Daud**

### Banking Transaction Analytics Using SQL

A comprehensive SQL project focused on banking transaction analysis, customer behavior insights, fraud detection, beneficiary analysis, and business intelligence reporting using relational databases.
