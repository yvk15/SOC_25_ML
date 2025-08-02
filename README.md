# SOC_25_ML

##  Final Project: Credit Card Fraud Detection & Customer Profiling

This project was built as part of the **Intro to Machine Learning** course. It focuses on solving two real-world problems using machine learning techniques:


##  1. Fraud Detection

We analyzed a real-world credit card transactions dataset to detect **fraudulent activities**.

🔸 Fraud is rare (less than **0.2%** of all transactions), making this a classic case of **imbalanced data**.  
🔸 We used the **Isolation Forest algorithm** – an unsupervised anomaly detection method – to identify suspicious transactions.  
🔸 The results were visualized to understand what makes certain transactions look fraudulent.


##  2. Customer Profiling

Using a separate dataset with customer behavior details (like credit card usage, visits, and calls), we performed:

- 🔹 **K-Means Clustering (custom implementation)** to segment customers into similar groups  
- 🔹 **Linear Regression** to predict a customer’s **average credit limit** based on their behavior


##  Why This Project?

This project combines two powerful ML applications:  
✔️ Detecting fraud to reduce risk and financial loss  
✔️ Understanding customers to improve services and personalization

What we learned:

- Handling real-world, messy and imbalanced data  
- Applying both **unsupervised** and **supervised** learning methods  
- Visualizing insights in a way that makes them easy to understand


##  Files Included

- `creditcard.csv` – Dataset for fraud detection (from Kaggle)  
- `Credit Card Customer Data.csv` – Dataset for customer profiling  
- `fraud_detection.ipynb` – Jupyter notebook for anomaly detection  
- `credit_profiling.ipynb` – Jupyter notebook for clustering and regression


##  Tech Stack

- Python  
- Jupyter Notebook  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (for selected tasks only)





