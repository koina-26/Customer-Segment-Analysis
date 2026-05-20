🛍️ Customer Segmentation using K-Means Clustering

📌 Project 

A machine learning project that segments customers based on real transactional behavior using K-Means clustering and RFM Analysis. Built on the Online Retail II dataset containing 5,41,909 real transactions, this project transforms raw purchase data into actionable business intelligence — identifying distinct customer groups and generating targeted marketing strategies for each segment.

🚀 Features

- Real RFM Analysis — Recency, Frequency, Monetary calculated from actual transaction dates
- K-Means Clustering using scikit-learn with the Elbow Method for optimal K selection
- Customer Segmentation into 4 distinct behavioral groups
- Purchase Pattern Analysis across all customer segments
- Product Preference Mapping — Top 5 products identified per segment
- Monthly Revenue Trend Analysis by customer segment
- Targeted Marketing Strategies with priority scoring per segment
- 9 Professional Visualizations covering all aspects of customer behavior

 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Scikit-learn | K-Means clustering and StandardScaler |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Google Colab | Development environment |

## 🔄 Workflow Flowchart

```
Raw Dataset (541909 transactions)
        |
        v
Data Cleaning
   |-- Remove null CustomerIDs
   |-- Remove cancelled orders
   |-- Remove negative quantities
   |-- Filter to UK customers
        |
        v
Exploratory Data Analysis
   |-- Monthly revenue trends
   |-- Top selling products
        |
        v
RFM Analysis
   |-- Recency   -> Days since last purchase
   |-- Frequency -> Number of unique orders
   |-- Monetary  -> Total amount spent
        |
        v
RFM Scoring (1 to 4 per metric)
   |-- Champions
   |-- Loyal Customers
   |-- At Risk
   |-- Needs Attention
   |-- Lost Customers
        |
        v
K-Means Clustering
   |-- StandardScaler - normalize RFM values
   |-- Elbow Method - find optimal K
   |-- K-Means with K=4 - assign clusters
        |
        v
Segment Naming
   |-- High Value VIPs
   |-- Loyal Regulars
   |-- At Risk Customers
   |-- Lost Customers
        |
        v
Analysis and Visualization
   |-- Purchase pattern charts
   |-- Product preferences per segment
   |-- Monthly revenue by segment
        |
        v
Targeted Business Insights
   |-- Marketing strategy per segment
   |-- Communication channel per segment
   |-- Business priority scoring
```
## 📂 Project Structure

```
Customer-Segment-Analysis
|
|-- README.md                        <- Project documentation
|-- customer_segment_analysis.py     <- Complete project code
|-- Online_Retail.xlsx               <- Dataset
|-- business_priority.png
|-- customer_clusters.png
|-- elbow_method.png
|-- monthly_by_segment.png
|-- monthly_revenue.png
|-- purchase_patterns.png
|-- rfm_distribution.png
|-- rfm_segments.png
|-- top_products.png
```

📚 Learning Outcomes

- Understood the concept and real-world application of customer segmentation
- Gained hands-on experience with unsupervised machine learning using K-Means
- Learned how to build a complete RFM Analysis pipeline from raw transaction data
- Practiced data cleaning techniques on a large real-world dataset
- Developed skills in data visualization using Matplotlib and Seaborn
- Learned how to translate data insights into actionable business strategies
- Built experience in structuring and presenting a complete data science project

🎯 Conclusion

This project successfully demonstrates how raw transactional data can be transformed into meaningful customer intelligence using unsupervised machine learning. By combining RFM Analysis with K-Means Clustering on the Online Retail II dataset, four distinct customer segments were identified — each with unique behavioral patterns and business value.

The segmentation revealed that a small group of High Value VIPs drives a disproportionate share of revenue. At the same time, a significant portion of customers are either at risk or already lost — highlighting the urgent need for targeted retention strategies. Rather than treating all customers the same, businesses can now use these segments to personalize communication, allocate marketing budgets more efficiently, and ultimately improve customer lifetime value.

This project builds a strong foundation in customer analytics, RFM modeling, and data-driven decision-making — skills that are directly applicable to roles across data science, business intelligence, and marketing analytics.
