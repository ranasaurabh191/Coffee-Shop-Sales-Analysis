# ☕ Coffee Shop Sales Analysis

## 📌 Project Overview
This project analyzes **coffee shop sales data** to uncover insights into customer behavior, product performance, and revenue trends. Using **Power BI** for data visualization and **MySQL** for backend data handling, it demonstrates how data-driven decisions can significantly optimize retail business operations.
The project focuses on real-time and historical data analysis, providing stakeholders with interactive dashboards that uncover patterns in **product popularity**, **peak business hours**, **revenue growth**, and **customer behavior**. This hands-on project showcases the power of business intelligence in the retail and food & beverage industry.

## 🎯 Project Objectives
- 📈 **Track and analyze daily, weekly, and monthly revenue trends**
- ⏰ **Identify peak sales hours and days of the week**
- 🛒 **Understand customer purchase behavior across time and product categories**
- ☕ **Rank top-performing products and categories**
- 🎯 **Deliver actionable business recommendations based on data insights**
- 💰 **Assist in inventory and staffing decisions through seasonal sales patterns**

## 🛠️ Tech Stack
- **MySQL** – Data extraction, cleaning, transformation, and querying 📂
- **Power BI** – Interactive dashboards and visual analytics 📈

## 💡 Challenges & Solutions
| Challenge | Solution |
|----------|----------|
| Inconsistent and messy sales data | Applied SQL techniques (`JOIN`, `GROUP BY`, `CASE`, `DATE_FORMAT`) to clean and normalize entries |
| Large dataset leading to slow dashboard performance | Used filters and modular design to enable smooth slicing and dynamic insights |
| Difficulty in detecting meaningful trends | Performed EDA using temporal and categorical grouping to reveal hidden patterns |

## 📁 Dataset
The dataset includes anonymized records of sales transactions, with fields such as:
- Order ID
- Product Name
- Category
- Sales Amount
- Date & Time
- Customer Demographics

## 🔄 Process Flow
1. **Data Collection** – Sales data imported into **MySQL**
2. **Data Cleaning & Transformation** – Structured using SQL queries
3. **Exploratory Data Analysis (EDA)** – Trends and anomalies identified
4. **Dashboard Development** – KPIs and charts created in **Power BI**
5. **Insight Generation** – Business recommendations extracted from visual analytics

## 📊 Dashboard Preview
[🔗 Power BI Dashboard Preview](https://app.powerbi.com/groups/me/reports/b87e2c71-d624-45a4-b0a1-aa592d95fee5/31314930792587844557?experience=power-bi)

## 📌 Key Insights
✔️ **Espresso** and **Latte** were the highest contributors to total revenue ☕  
✔️ Peak sales occurred during **morning (8–10 AM)** and **evening (4–6 PM)** rush hours ⏰  
✔️ **Weekend sales** were significantly higher due to leisure-based purchases 🛒  
✔️ Seasonal trends indicated a slight decline in sales during **summer months** 📅  
✔️ Targeted promotions could improve performance in **low-traffic hours**

## 🚀 How to Run the Project
1. **Clone the repository**  
   ```bash
   git clone https://github.com/ranasaurabh191/coffee-shop-sales.git
