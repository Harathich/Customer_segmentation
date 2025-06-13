# 🛍️ Customer Segmentation Project

This project focuses on segmenting customers based on their purchasing behavior to help businesses better understand their customer base, enhance marketing strategies, and improve customer retention.

---

## 📊 Project Overview

Customer segmentation is an essential component of business intelligence. In this project, machine learning algorithms are used to group customers based on:

- Demographics  
- Purchase behavior  
- Recency, Frequency, and Monetary value (RFM)  
- Churn likelihood  

This approach helps in creating targeted marketing campaigns and developing personalized customer experiences.

---

## 🧰 Features

### 🗂️ Dataset
The project uses a simulated dataset that includes:
- Customer demographics (age, gender)  
- Purchase history (product categories, price, quantity)  
- Payment method  
- Churn indicator  
- Return history  

### 📈 Key Metrics Computed
- **Recency**: Days since the last purchase  
- **Frequency**: Number of purchases made  
- **Monetary Value**: Total amount spent  

These metrics are then used for RFM analysis.

---

## 🔧 Technologies Used

- **Language**: Python  
- **Libraries**:
  - pandas, numpy – data handling  
  - matplotlib, seaborn – data visualization  
  - scikit-learn – clustering algorithms & preprocessing  

---

## 🧠 Machine Learning Algorithms

- **K-Means Clustering**: For unsupervised customer grouping  
- **DBSCAN**: Density-based clustering for identifying outlier customers  

---

## 📊 Visualizations

- RFM distribution plots  
- Clustering plots with centroids  
- Heatmaps for feature correlation  
- Elbow method for optimal clusters  
- DBSCAN epsilon neighborhood analysis  

---

## 🚀 Installation and Usage

```bash
# Clone the repository
git clone https://github.com/Harathich/Customer_segmentation.git
cd Customer_segmentation

# Install the required dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Datamining.ipynb

