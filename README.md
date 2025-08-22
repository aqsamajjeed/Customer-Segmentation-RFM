# 🛍️ Customer Segmentation Using RFM Analysis  

## 📌 Project Overview  
This project focuses on **RFM Analysis (Recency, Frequency, Monetary)** to understand customer purchasing behavior and segment them into meaningful groups. By applying this approach to the **UCI Online Retail Dataset**, we identify key customer groups and provide insights for personalized marketing strategies.  

## 📂 Dataset  
- **Source:** Online Retail Dataset (UCI Machine Learning Repository)  
- **Period:** Transactions between December 2010 and December 2011  
- **Attributes:** Invoice number, stock code, quantity, invoice date, unit price, customer ID, and more.  

## 🛠️ Tools & Libraries  
- Python (Pandas, Numpy, Seaborn, Matplotlib)  
- Excel file handling with OpenPyXL  
- Jupyter/Colab for analysis and visualization  

## 🔑 Project Workflow  

### 1. Data Cleaning  
- Removed rows with missing customer IDs  
- Filtered out canceled orders and negative quantities  
- Created a new field for total revenue per transaction  

### 2. Feature Engineering  
- Defined **Recency** (days since last purchase), **Frequency** (number of transactions), and **Monetary** (total spend).  
- Generated aggregated RFM values per customer.  

### 3. RFM Scoring  
- Assigned scores (1–4) for each RFM dimension using quartile-based segmentation.  
- Recency scores were reversed so recent purchases receive higher values.  
- Computed an overall RFM Score by summing the three components.  

### 4. Customer Segmentation  
Based on RFM scores, customers were segmented into the following groups:  
- **Best Customers** – High across all three metrics, top priority for retention.  
- **Loyal Customers** – Regular buyers with strong frequency scores.  
- **Potential Loyalists** – Customers showing potential to grow with engagement.  
- **Needs Attention** – Customers at risk of churn, requiring reactivation.  

### 5. Visualization  
- Distribution of customer segments plotted using Seaborn bar charts.  
- Clear insights into which segments contribute most to revenue and engagement.  

### 6. Results Export  
- Final customer segmentation table saved as a CSV for further use in marketing strategy.  

## 📊 Key Insights  
- A small cluster of **Best Customers** drives a large share of revenue.  
- **Potential Loyalists** present an opportunity for growth with tailored offers.  
- **Needs Attention** customers highlight retention challenges.  

## 🎯 Marketing Ideas by Segment  
- **Best Customers:** Exclusive rewards, VIP programs, early access to sales.  
- **Loyal Customers:** Special discounts, loyalty points, personalized thank-you messages.  
- **Potential Loyalists:** Targeted upsell offers, referral programs, onboarding campaigns.  
- **Needs Attention:** Win-back emails, limited-time offers, personalized re-engagement strategies.  

## 📌 Learning Outcomes  
- Hands-on practice with feature engineering, segmentation, and RFM logic.  
- Experience in business-focused customer analytics.  
- Application of Python and visualization libraries to derive actionable insights.  
