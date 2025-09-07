# ML-Credit-Card-Clustering
# 💳 Credit Card Clustering with Machine Learning  

## 📌 Project Overview  
Credit Card Clustering (or segmentation) is the process of **grouping credit card holders** based on their:  
- Buying habits  
- Credit limits  
- Overall financial behavior  

This analysis is valuable for **customer segmentation, targeted marketing, and product personalization** in the banking and finance industry.  

---

## 🎯 Problem Statement  
Banks and financial organizations often struggle to identify customer groups for:  
- Personalized offers  
- Credit limit recommendations  
- Fraud detection & spending pattern analysis  

This project leverages **unsupervised machine learning (K-Means clustering)** to analyze and segment customers effectively.

---

## 🛠 Project Workflow  
1. **Data Collection**  
   - Dataset includes balance, purchases, and credit limits of customers.  

2. **Data Cleaning & Preprocessing**  
   - Handled **missing values** in key fields like `Minimum Payments` and `Credit Limit`.  

3. **Feature Engineering**  
   - Selected features:  
     - `BALANCE` – Remaining balance in customer accounts.  
     - `PURCHASES` – Total purchases made by customers.  
     - `CREDIT_LIMIT` – Assigned credit card limit.  

4. **Clustering with K-Means**  
   - Normalized the dataset using `MinMaxScaler`.  
   - Created **5 distinct clusters** of credit card users.  

5. **Visualization**  
   - 3D visualization of clusters using **Plotly** for better insight into customer segments.  

---

## 📊 Insights  
- Clusters reveal distinct customer groups based on **spending power and usage**.  
- High-balance, low-purchase clusters represent **low engagement users**.  
- High-purchase, high-credit users are **premium customers** and can be targeted for loyalty programs.  

---

## ⚙️ Tech Stack  
- **Python Libraries:** Pandas, NumPy, Scikit-learn, Plotly  
- **ML Algorithm:** K-Means Clustering  
- **Visualization:** Plotly 3D Scatter Plot  
- **Dataset:** Public Credit Card Usage Dataset  

---

## 🚀 Deliverables  
✅ Cleaned and processed dataset for clustering  
✅ K-Means model with **5 clusters**  
✅ 3D interactive visualization of customer segments  
✅ Business-ready insights for **targeted marketing strategies**  

---

## 📈 Business Impact  
This project empowers financial institutions to:  
- Personalize offers based on customer behavior  
- Increase customer retention through engagement strategies  
- Optimize risk management and credit assignment  

---
