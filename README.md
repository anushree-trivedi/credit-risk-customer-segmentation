# credit-risk-customer-segmentation
Customer Segmentation using K-means clustering on 8,950 credit card customers - Python, Power BI

# Credit Card Customer Segmentation
### Risk & Value Analysis | 8,950 Customers

## 📌 Business Problem
A credit card company treats all customers the same however a high-value 
customer who pays in full deserves different treatment than a high-risk 
customer carrying maximum balance. This project uses machine learning to 
segment customers by financial behavior and deliver actionable business strategy.

## 🛠️ Tools Used
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- K-Means Clustering
- PCA (Dimensionality Reduction)
- Power BI (Dashboard)

## 📊 Dashboard Preview
![Dashboard](dashboard_screenshot.png)

## 🔍 Customer Segments Identified

| Segment | Count | Avg Credit Limit | Business Action |
|---|---|---|---|
| 🟢 High Value — Full Payers | 409 | $9,700 | Loyalty rewards, credit limit increase |
| 🔴 High Risk — Revolvers | 3,977 | $3,300 | Monitor delinquency, hardship programs |
| 🟡 Moderate — Occasional Spenders | 1,197 | $7,500 | Re-engagement campaigns |
| 🔵 Low Engagement — Dormant | 3,367 | $4,200 | Win-back campaigns, account review |

## 💡 Key Insights
- 44% of customers are High Risk Revolvers — largest segment requiring immediate attention
- High Value customers have 3x the credit limit of High Risk customers
- Dormant segment represents significant lost revenue opportunity

## 📁 Files
- `customer_segmentation.ipynb` — Full Python analysis
- `customer_segments_output.csv` — Segmented dataset
- `dashboard_screenshot.png` — Power BI dashboard
