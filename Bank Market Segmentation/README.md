# Customer Segmentation for Targeted Marketing using Data Science

## 📌 Project Overview
Marketing is crucial for the growth and sustainability of any business. One of the biggest challenges for marketers is **understanding customers and identifying their needs**.  
This project focuses on **customer segmentation** using data science techniques to help a bank launch **targeted marketing campaigns**.

In this case study, we act as a **data science consultant** hired by a **bank in New York City**, which has collected extensive customer transaction data over the past **6 months**.  
The goal is to divide customers into **at least 3 meaningful segments** based on their credit card usage behavior.

---

## 🎯 Objective
- Understand customer spending and payment behavior
- Segment customers into distinct groups
- Enable **targeted and personalized marketing campaigns**
- Improve customer engagement and sales conversion

---

## 🏦 Business Use Case
- Bank wants to launch **targeted advertisements**
- Customers behave differently in terms of:
  - Spending
  - Installments
  - Cash advances
  - Payments
- Treating all customers the same leads to **inefficient marketing**
- Segmentation helps the bank:
  - Offer the right product to the right customer
  - Improve customer satisfaction
  - Increase revenue

---

## 🧠 Key Concepts Used
- Exploratory Data Analysis (EDA)
- Feature Understanding
- Data Preprocessing & Scaling
- Unsupervised Learning
- **Customer Segmentation using Clustering**

---

## 📊 Dataset Description
Each row represents a **credit card customer**.  
Below are the main features used:

### Customer Information
- **CUSTID**: Unique identification of the credit card holder
- **TENURE**: Duration (in months) of credit card service

### Balance & Spending
- **BALANCE**: Remaining balance in the customer’s account
- **BALANCE_FREQUENCY**: Frequency of balance updates (0–1)
- **PURCHASES**: Total purchase amount
- **ONEOFF_PURCHASES**: Maximum single purchase amount
- **INSTALLMENTS_PURCHASES**: Amount spent via installments

### Purchase Behavior
- **PURCHASES_FREQUENCY**: Frequency of purchases (0–1)
- **ONEOFF_PURCHASES_FREQUENCY**: Frequency of one-time purchases
- **PURCHASES_INSTALLMENTS_FREQUENCY**: Frequency of installment purchases

### Cash Advance Behavior
- **CASH_ADVANCE**: Cash withdrawn using credit card
- **CASH_ADVANCE_FREQUENCY**: Frequency of cash advances
- **CASH_ADVANCE_TRX**: Number of cash advance transactions

### Transaction & Payment Details
- **PURCHASES_TRX**: Number of purchase transactions
- **CREDIT_LIMIT**: Credit limit assigned to the customer
- **PAYMENTS**: Total amount paid by the customer
- **MINIMUM_PAYMENTS**: Minimum payment amount
- **PRC_FULL_PAYMENT**: Percentage of full payment done

---

## 🔍 Problem Statement
> Segment customers into **at least 3 distinct groups** based on their credit card behavior to enable targeted marketing.

---

## ⚙️ Approach
1. **Data Cleaning**
   - Handle missing values
   - Remove irrelevant columns
2. **Feature Scaling**
   - Standardization to bring features to the same scale
3. **Clustering**
   - Apply clustering algorithm (e.g., K-Means)
4. **Cluster Analysis**
   - Interpret each customer segment
5. **Business Insights**
   - Convert clusters into actionable marketing strategies

---

## 📈 Expected Customer Segments (Example)
- **High-value customers**  
  High spending, frequent full payments
- **Installment-based customers**  
  Prefer EMI and installment purchases
- **Cash-advance dependent customers**  
  Frequently withdraw cash with higher risk

---

## 🚀 Impact
- Enables **data-driven marketing**
- Improves campaign conversion rate
- Reduces marketing cost
- Enhances customer experience

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📌 Conclusion
This project demonstrates how **data science can transform raw customer transaction data into meaningful business insights**.  
Customer segmentation helps organizations move from **generic marketing to personalized engagement**, leading to better growth and sustainability.

---

## 👤 Author
**Aviral Mittal**  
Data Science | Machine Learning | Business Analytics

---

## ⭐ If you like this project
Give it a ⭐ on GitHub and feel free to fork or contribute!
