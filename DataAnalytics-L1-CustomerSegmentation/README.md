# 📊 Customer Segmentation Analysis 

## 📌 Project Overview

This project was completed as part of the **Oasis Infobyte Data Analytics Internship**.

The objective of this project is to segment an e-commerce company's customers into distinct groups based on their purchasing behavior using **RFM (Recency, Frequency, Monetary) Analysis** and the **K-Means Clustering** algorithm. These customer segments help businesses create targeted marketing strategies and improve customer retention.

---

## 🎯 Objectives

- Analyze customer purchasing behavior using RFM Analysis.
- Perform customer segmentation using K-Means Clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Visualize customer segments.
- Profile each customer cluster.
- Provide marketing recommendations for each customer segment.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (K-Means, StandardScaler)

---

## 📂 Dataset

**Dataset:** Online Retail Dataset

The dataset contains transaction records including:

- Customer ID
- Invoice Number
- Invoice Date
- Quantity
- Unit Price
- Product Description
- Country

---

## 📈 Project Workflow

### 1. Data Loading

- Imported the dataset using Pandas.
- Inspected dataset structure.
- Checked missing values.
- Removed records with missing Customer IDs.

### 2. Data Preparation

- Created a new **Sales** column.
- Converted InvoiceDate into datetime format.
- Calculated the reference date for Recency.

### 3. RFM Analysis

Calculated three customer behavior metrics:

- **Recency** – Number of days since the customer's last purchase.
- **Frequency** – Total number of purchases made.
- **Monetary** – Total amount spent by each customer.

### 4. Data Standardization

Applied **StandardScaler** to normalize the RFM features before clustering.

### 5. Customer Segmentation

- Applied the Elbow Method to determine the optimal number of clusters.
- Built a K-Means clustering model.
- Assigned each customer to a cluster.

### 6. Data Visualization

Generated visualizations including:

- Elbow Method Curve
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Number of Customers per Cluster

### 7. Cluster Profiling

Calculated the average Recency, Frequency, and Monetary values for each customer segment and identified different customer types.

---

## 📊 Customer Segments

### Cluster 0 – Loyal Customers
- Recent purchases
- High purchase frequency
- High spending

**Marketing Strategy**
- Loyalty reward programs
- Personalized product recommendations
- Exclusive discounts

---

### Cluster 1 – Inactive / At-Risk Customers
- Long time since last purchase
- Low purchase frequency
- Low spending

**Marketing Strategy**
- Re-engagement campaigns
- Discount coupons
- Promotional offers

---

### Cluster 2 – VIP / High-Value Customers
- Very recent purchases
- Extremely high purchase frequency
- Highest spending

**Marketing Strategy**
- VIP membership
- Premium customer support
- Early access to new products
- Exclusive rewards

---

## 📈 Key Insights

- Most customers belong to the Loyal Customer segment.
- A small number of customers generate exceptionally high revenue, making them valuable VIP customers.
- Some customers have become inactive and require targeted marketing campaigns to encourage repeat purchases.

---

## 💡 Business Recommendations

- Focus on retaining VIP customers with exclusive benefits.
- Reward loyal customers to increase long-term retention.
- Re-engage inactive customers through personalized marketing campaigns and promotional offers.

---

## 📁 Repository Structure

```
DataAnalytics-L1-CustomerSegmentation/
│
├── Customer_Segmentation_Analysis.ipynb
├── online_retail.csv
├── README.md
├── images/
│   ├── elbow_method.png
│   ├── cluster_scatterplot.png
│   └── customer_clusters.png

```


---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/muhammad-ali-ds/OIBSIP.git

```

2. Navigate to the project folder.

```bash
cd DataAnalytics-L1-CustomerSegmentation
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all cells to reproduce the analysis.

---

## 📸 Output

The notebook includes:

- Cleaned and prepared dataset
- RFM Analysis
- Elbow Method
- K-Means Clustering
- Cluster Visualizations
- Customer Profiles
- Marketing Recommendations

---

## 👨‍💻 Author

**Muhammad Ali**

**Data Analytics Intern**

**Oasis Infobyte**

GitHub: https://github.com/muhammad-ali-ds

LinkedIn:  https://linkedin.com/in/muhammad-ali-175691383

---

## ⭐ Internship Information

**Organization:** Oasis Infobyte

**Track:** Data Analytics

**Level:** Level 1

**Task:** Task 2 – Customer Segmentation Analysis

**Algorithm:** K-Means Clustering

---
