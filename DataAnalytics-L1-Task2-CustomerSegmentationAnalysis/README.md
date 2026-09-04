# Task 2 — Customer Segmentation Analysis

This project is completed as part of my **Data Analytics Internship at Oasis Infobyte (OIBSIP)**.

## Objective

The objective of this project is to segment customers based on their purchasing behaviour using **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering**.

The analysis aims to identify meaningful customer segments and develop actionable marketing strategies for each segment.

## Dataset

**Dataset:** Online Retail Dataset (obtained from kaggle)
Source: https://www.kaggle.com/datasets/ersany/online-retail-dataset

The dataset contains transaction-level information such as:

- Invoice Number
- Stock Code
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

1. Loaded and inspected the dataset
2. Checked missing values and duplicate records
3. Cleaned the transaction data
4. Removed cancelled transactions and invalid records
5. Calculated total purchase amount
6. Performed customer-level descriptive analysis
7. Conducted RFM analysis
8. Standardized RFM features using `StandardScaler`
9. Used the Elbow Method to determine a suitable number of clusters
10. Applied K-Means clustering
11. Visualized customer clusters using scatter plots
12. Created cluster profiles
13. Analyzed the number of customers in each cluster
14. Interpreted the customer segments
15. Developed marketing recommendations for each segment

## RFM Analysis

RFM analysis was used to understand customer purchasing behaviour:

- **Recency:** How recently a customer made a purchase
- **Frequency:** How often a customer made a purchase
- **Monetary:** How much a customer spent

These three metrics were used as the main features for customer segmentation. :contentReference[oaicite:2]{index=2}

## K-Means Clustering

**K-Means** was used to group customers with similar purchasing behaviour.

Before clustering, the RFM features were standardized using **StandardScaler** because the three variables have different numerical scales.

The **Elbow Method** was used to select a suitable value of K before applying K-Means clustering. :contentReference[oaicite:3]{index=3}

## Customer Segments

The resulting clusters were interpreted into meaningful business segments such as:

- High-value / Loyal Customers
- Recent / Promising Customers
- At-risk Customers
- Low-engagement Customers

## Business Recommendations

Different marketing strategies can be applied to different customer segments:

- **High-value customers:** Retention and loyalty programs
- **Recent customers:** Engagement, cross-selling, and repeat-purchase campaigns
- **At-risk customers:** Win-back and reactivation campaigns
- **Low-engagement customers:** Cost-efficient promotional and remarketing campaigns

The segmentation helps businesses prioritize marketing resources according to customer value and engagement. :contentReference[oaicite:4]{index=4}

## Key Learning

Through this project, I developed practical understanding of:

- Customer segmentation
- RFM analysis
- Feature scaling
- K-Means clustering
- Elbow Method
- Cluster profiling
- Data visualization
- Translating analytical results into business recommendations


## Author

**Shreya Agrawal**

Aspiring Data Analyst | MCA (AI & ML) Student

