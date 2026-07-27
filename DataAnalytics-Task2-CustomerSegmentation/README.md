# Task 2: Customer Segmentation Analysis

## 👤 Author
**Sharvari Gaikwad**
Data Analytics Intern @ Oasis Infobyte

## 🎯 Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour, enabling targeted marketing strategies.

## 🛠 Tools Used
- Python
- Pandas
- Scikit-learn (KMeans)
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧹 Workflow
1. Loaded the dataset and inspected its structure; handled missing values and inconsistent data.
2. Calculated descriptive statistics — average purchase value, purchase frequency, and customer lifetime value.
3. Performed **RFM analysis** (Recency, Frequency, Monetary) to identify key behavioural features for clustering.
4. Standardised the features using `StandardScaler` before clustering.
5. Applied **K-Means clustering**, using the Elbow Method to determine the optimal number of clusters (K).
6. Visualised the resulting clusters using scatter plots across multiple feature combinations.
7. Profiled each cluster by calculating mean feature values and describing the customer type.
8. Created a bar chart showing the number of customers per cluster.
9. Derived marketing recommendations tailored to each customer segment.

## 🔑 Key Insights
- The customer base was segmented into three distinct groups using RFM analysis and K-Means clustering.
- **Regular Customers** formed the largest segment, with 3,231 customers.
- **At-Risk Customers** represented 1,082 customers and showed the highest average recency of 247.11 days, indicating a need for re-engagement campaigns.
- **High-Value Loyal Customers** were the smallest segment, with only 26 customers, but had extremely high purchase frequency and monetary value — an average frequency of 66.50 purchases and an average monetary value of £85,904.35.
- RFM-based customer segmentation can help businesses create targeted marketing strategies for different customer groups.

## 📁 Files Included
| File | Description |
|------|-------------|
| `DataAnalytics_Task2_Customer_Segmentation.ipynb` | Jupyter Notebook with the full clustering workflow |
| `README.md` | Project documentation |

## 🏷 Internship
This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)** — Task 2.
