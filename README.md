# ecommerce-customer-sales-analytics
Interactive Power BI dashboard analyzing customer behavior and revenue trends — covering category-wise revenue, customer type segmentation, payment methods, gender-wise sales, and order status.

# 💳 Customer & Revenue Analysis Dashboard

An interactive Power BI dashboard analyzing customer behavior and revenue performance for an e-commerce business, covering category-wise revenue, customer segmentation, payment preferences, and order fulfillment status.

![Dashboard Preview](dashboard-preview.png)

## 📊 Overview

This project presents a **customer and revenue analytics dashboard** built in **Power BI**, designed to help understand which product categories, customer segments, and payment methods drive the most revenue — along with delivery performance and gender-based purchasing trends.

## ✨ Features / Visuals

- **Revenue by Category** — Electronics, Sports, Fashion, Home & Kitchen, Beauty
- **Gen vs Revenue (Customer Table)** — Customer-wise total amount spent and order count
- **City Wise Revenue** — Revenue breakdown by city
- **Customer Type (Pie Chart)** — Returning, New, Loyal, VIP segmentation
- **Customer Type by Payment Method (Donut Chart)** — Credit Card, Cash on Delivery, Debit Card share
- **Gen vs Revenue (Female vs Male)** — Gender-wise revenue comparison
- **Gen vs Revenue (Order Status)** — Delivered, Cancelled, Returned order counts

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard design & visualization
- **DAX (Data Analysis Expressions)** — Custom measures and aggregations
- **Power Query** — Data cleaning and transformation

## 📁 Repository Structure

```
├── Customer_Revenue_Analysis.pbix   # Power BI project file
├── dataset/                         # Raw/cleaned data used (if included)
├── dashboard-preview.png            # Dashboard screenshot
└── README.md
```

## 🔍 Key Insights

- **Electronics** is the top revenue-generating category (0.55M), followed by Sports (0.24M).
- **Returning customers (43.33%)** make up the largest customer segment, followed by Loyal customers (30%).
- **Female customers generate more revenue (0.55M)** than male customers (0.46M).
- Out of total orders, the majority (63) were **Delivered**, while 20 were Cancelled and 17 Returned.
- Total revenue across all customers stands at **₹10,12,177.30**.

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/customer-revenue-analysis-dashboard.git
   ```
2. Open `Customer_Revenue_Analysis.pbix` in **Power BI Desktop**
3. Use the filters/slicers to explore revenue by category, customer type, or city

## 📌 Future Improvements

- Add month-over-month revenue trend analysis
- Include customer lifetime value (CLV) calculation
- Publish dashboard to Power BI Service for web access

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
⭐ If you found this project useful, consider giving it a star on GitHub!
