# Customer Segmentation using Clustering (K-Means)

This project applies **K-Means Clustering** to segment mall customers based on their demographics and spending behavior. Customer segmentation helps businesses understand their customers better and design personalized strategies.

---

## 📂 Dataset
- Dataset: **Mall_Customers.csv**
- Features:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🚀 Project Workflow
1. **Data Exploration (EDA)**  
   - Checked data types, missing values, summary statistics.  
   - Visualized distributions of Age, Income, and Spending Score.  

2. **Data Preprocessing**  
   - Selected features (`Age`, `Annual Income`, `Spending Score`)  
   - Standardized data using `StandardScaler`.  

3. **K-Means Clustering**  
   - Used **Elbow Method & Silhouette Score** to determine optimal clusters.  
   - Chose `k = 5`.  

4. **Cluster Analysis**  
   - Identified customer groups:  
     - 🏆 High Income, High Spending  
     - 💸 High Income, Low Spending  
     - 🎯 Low Income, High Spending  
     - 📉 Low Income, Low Spending  
     - 👨‍👩‍👧 Moderate Customers  

---

## 📊 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📌 Business Insights
- Businesses can identify **premium customers** and reward loyalty.  
- Target **budget-conscious groups** with discounts.  
- Personalize marketing strategies for each cluster.  

---

## 📎 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-Clustering.git
   cd Customer-Segmentation-Clustering
