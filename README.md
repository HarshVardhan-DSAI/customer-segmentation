#  Customer Segmentation using K-Means Clustering

Unsupervised machine learning project to segment customers based on their **annual income** and **spending score**, helping businesses better target marketing strategies.

---

##  **Project Goal**
To identify distinct groups of customers who behave similarly, so businesses can:
- Create targeted marketing campaigns
- Personalize offers
- Improve customer satisfaction and profitability

---

##  **Dataset**
Dataset contains 200 customer records with the following features:

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1–100) |
|-----------:|:------:|---:|------------------:|----------------------:|
| 1 | Male   | 19 | 15 | 39 |
| 2 | Male   | 21 | 15 | 81 |
| 3 | Female | 20 | 16 | 6 |
| 4 | Female | 23 | 16 | 77 |
| 5 | Female | 31 | 17 | 40 |
| ... | ... | ... | ... | ... |

*(Source: Mall Customer Segmentation Data — widely used for clustering practice)*

---

##  **Method**
- Data exploration and cleaning
- Applied **K-Means clustering** to segment customers
- Used the **Elbow Method** to find the optimal number of clusters
- Visualized clusters using scatter plots to understand customer groups

---

##  **Results**
- Identified **5 distinct customer segments**, including:
  - High-income, high-spending customers
  - Low-income, low-spending customers
  - Moderate-income customers with varying spending habits
- Clusters help the business understand and target each group differently:
  - Reward loyal high spenders
  - Create offers for low-spending customers to increase engagement

---

## 🧪 **How to Run**
1. Clone the repository:
```bash
git clone https://github.com/HarshVardhan-DSAI/customer-segmentation.git
