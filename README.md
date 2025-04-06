# Customer Segmentation and Consumer Behavior Analysis

This project applies data analytics and machine learning techniques to segment customers based on their buying behavior and identify the key drivers of sales using the 80/20 rule (Pareto Principle).

---

## 🔍 Project Overview

This analysis involves two primary topics:

### 📌 Topic 1: Customer Segmentation Using K-Means Clustering

**Objective:**  
Segment customers based on their purchasing behavior using an unsupervised learning algorithm (K-Means clustering), and identify patterns that inform strategic business decisions.

**Dataset:**  
[Wholesale Customers Data Set](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)

**Methodology:**
- Preprocessed the dataset by standardizing the features.
- Applied the **Elbow Method** to determine the optimal number of clusters.
- Performed **K-Means Clustering** to group customers based on spending on categories like Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen.
  
**Key Insights:**
- **3 optimal clusters** were identified.
- **Segment 1**: High spenders on Milk, Grocery, and Detergents_Paper.
- **Segment 2**: Significant purchases in Fresh, Frozen, and Delicatessen.
- **Segment 3**: Moderate purchasers, potentially saturated or competitive market segment.
- Region was **not a significant factor** in customer segmentation as most customers came from Region 3.

**Business Strategy:**
- Focus marketing and promotional efforts on Segments 1 and 2 for potential growth.
- Competitive strategies may be needed to engage customers in Segment 3.

---

### 📌 Topic 2: Applying the 80/20 Rule to Analyze Sales Performance

**Objective:**  
Use the Pareto Principle to identify the top customers, products, and countries that contribute to 80% of total revenue.

**Dataset:**  
[Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/online+retail)

**Key Findings:**

#### Customers:
- Top 25% of customers (1,084 out of 3,877) generated approximately **79% of total sales revenue**.

#### Products:
- Top 20% of products (775 out of 3,877) contributed to **79% of total revenue**.

#### Geographic Locations:
- **UK** alone generated **82% of the company’s total revenue**, as expected for a UK-based retailer.
- Other top-performing countries include the Netherlands, Ireland (EIRE), Germany, and France.

**Business Strategy:**
- Focus on **top customers and products** for loyalty and retention initiatives.
- Consider **expanding operations** in top-performing countries outside the UK for strategic geographic growth.

---

## 🧠 Techniques Used

- **Unsupervised Learning (K-Means Clustering)**
- **Data Preprocessing and Normalization**
- **Elbow Method for Optimal Clustering**
- **Pareto Analysis (80/20 Rule)**
- **Data Aggregation and Filtering using Pandas**

---

## 📈 Conclusion

This project successfully segments customers based on their buying behavior and identifies key drivers of sales using the 80/20 rule. The clustering analysis provides insights into spending patterns, helping target high-value customers and prioritize growth areas. The Pareto analysis highlights which customers, products, and countries contribute the most to revenue, offering a clear path for strategic decision-making.

---

## 🚀 Future Enhancements

- Apply **RFM (Recency, Frequency, Monetary)** analysis for refined customer segmentation.
- Use **dimensionality reduction** techniques like PCA before clustering to improve accuracy.
- Integrate **interactive dashboards** using Tableau or Power BI to visualize clusters and insights.
- Explore alternative clustering techniques like **Hierarchical Clustering** or **DBSCAN**.
- Include **time-series analysis** to capture seasonal trends in purchasing behavior.

---

## 📂 Repository Structure

```bash
├── Consumer_buying_behavior_Paul.ipynb   # Jupyter Notebook with analysis
├── wholesale_customers.csv              # Dataset 1: Customer features
├── online_retail.csv                    # Dataset 2: Sales transactions
├── README.md                            # Project overview and insights
