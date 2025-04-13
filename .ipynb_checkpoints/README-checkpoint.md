# **Enhanced Business Analysis Project**  

## **Introduction**  
This project provides a **data-driven approach** to understanding business purchasing behavior, product performance, and market trends. By leveraging **advanced analytics**, we segment businesses, forecast sales, detect anomalies, and derive actionable insights to **enhance customer engagement, retention, and operational efficiency**.  

### **Key Objectives**  
✔ **Business Segmentation** – Classify businesses into **High, Medium, and Low Value** segments.  
✔ **Sales Forecasting** – Predict future sales trends using **time-series models**.  
✔ **Anomaly Detection** – Identify unusual purchasing patterns and investigate causes.  
✔ **Product Performance** – Analyze top-performing products and seasonal trends.  
✔ **Location-Based Insights** – Optimize sales strategies based on regional performance.  
✔ **Strategic Recommendations** – Provide data-backed decisions to improve business outcomes.  

---

## **Background & Problem Statement**  
Understanding customer purchasing behavior is crucial for optimizing **marketing, inventory, and sales strategies**. This project addresses:  

### **Key Business Questions**  
1. **How can businesses be segmented based on purchasing behavior?**  
2. **What are the expected sales for the next three months?**  
3. **Are there anomalies in purchasing trends? What causes them?**  
4. **How does quantity sold relate to total revenue?**  
5. **Which products perform best, and what are their seasonal trends?**  
6. **Which locations generate the highest sales, and why?**  

### **Dataset Used**  
📂 **[Cleaned Dataset](Data/Cleaned_data.csv)**  

---

## **Methodology & Tools**  

### **1. Business Segmentation**  
- **K-Means Clustering** to classify businesses into:  
  - **High Value** (High revenue, frequent purchases)  
  - **Medium Value** (Moderate engagement)  
  - **Low Value** (Low revenue, infrequent purchases)  
- **RFM (Recency, Frequency, Monetary) Analysis** for customer prioritization.  

### **2. Sales Forecasting**  
- **ARIMA & Moving Averages** for time-series predictions.  
- **Seasonal Decomposition** to identify trends and cyclical patterns.  

### **3. Anomaly Detection**  
- **Z-Score Analysis** for outlier detection.  
- **Isolation Forest Algorithm** to flag unusual transactions.  

### **4. Product & Location Analysis**  
- **Correlation Analysis** between quantity sold and revenue.  
- **Geospatial Insights** to identify high-performing regions.  

### **Tools & Technologies**  
- **Python** (Pandas, NumPy, Scikit-learn, Statsmodels)  
- **Data Visualization** (Matplotlib, Seaborn, Plotly)  
- **Dashboarding** (Power BI)  
- **Machine Learning** (Clustering, Forecasting, Anomaly Detection)  

---

## **Key Insights & Findings**  

### **📊 Business Segmentation Insights**  
- **High-Value Businesses (20%)** → Contribute **70% of revenue** (e.g., `Business-978e`).  
- **Medium-Value (30%)** → Moderate but consistent buyers.  
- **Low-Value (50%)** → Require re-engagement strategies.  

📌 **Recommendation:**  
- **Personalized offers** for High-Value customers.  
- **Loyalty programs** to boost Medium-Value buyers.  
- **Discounts & outreach** to reactivate Low-Value businesses.  

---

### **📈 Sales Forecasting & Trends**  
- **Next 3-Month Forecast:** Expected **10% growth** in `Category-75`.  
- **Seasonal Peaks:** Higher sales in **Q4** (holiday season).  

📌 **Recommendation:**  
- **Stock optimization** for high-demand periods.  
- **Promotional campaigns** ahead of peak seasons.  

---

### **⚠️ Anomaly Detection Findings**  
- **Sudden drops** in `Business-cb1f` (-$2.6M) due to **supply chain issues**.  
- **Spikes** in `Category-100` linked to **limited-time promotions**.  

📌 **Recommendation:**  
- **Root-cause analysis** for anomalies.  
- **Dynamic pricing adjustments** during demand fluctuations.  

---

### **📦 Product Performance Analysis**  
✅ **Top Performers:**  
- `Product-6069` (KES 2.5M sales)  
- `Product-875` (High demand in Q3)  

❌ **Low Performers:**  
- `Product-1413` (Minimal sales)  

📌 **Recommendation:**  
- **Bundle low-performing products** with best-sellers.  
- **Phase out underperforming SKUs**.  

---

### **📍 Location-Based Insights**  
🏆 **Top Locations:**  
- `Location-689f` (KES 264M sales)  
- `Location-3e32` (KES 202M sales)  

📌 **Recommendation:**  
- **Expand inventory** in high-performing regions.  
- **Investigate underperforming areas** for improvement opportunities.  

---

## **Dashboard & Reporting**  
📊 **[Power BI Dashboard](python _files/BUSINESS ANALYSIS.pbit)**  

![Dashboard Screenshot](Assets/my_dashboard.png)  

### **Dashboard Features:**  
✔ **Interactive sales trends**  
✔ **Business segmentation breakdown**  
✔ **Anomaly alerts**  
✔ **Product & location performance**  

---

## **Conclusion & Future Work**  
This analysis provides **actionable insights** to optimize sales, marketing, and inventory strategies.  

### **Next Steps:**  
🔹 **Real-time sales tracking** for dynamic adjustments.  
🔹 **Predictive ML models** for customer churn prevention.  
🔹 **Automated anomaly alerts** for proactive decision-making.  

---

### **🎯 Why This Matters for Businesses?**  
✅ **Increase Revenue** by targeting high-value customers.  
✅ **Reduce Costs** by optimizing inventory.  
✅ **Improve Retention** with data-driven engagement strategies.  
