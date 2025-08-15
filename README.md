# Slice-QL
Pizza Sales Analytics is a SQL-driven project analyzing pizza sales data to uncover trends, optimize inventory, and boost revenue. Features complex queries, aggregations, and visual insights to demonstrate data management and analytical skills.

# 🍕 Pizza sales Analytics

**Pizza sales Analytics** is a SQL-driven portfolio project that analyzes pizza sales data to uncover trends, optimize inventory, and boost revenue. It demonstrates advanced query writing, aggregations, joins, and insights generation, making it perfect for showcasing SQL and data analytics skills.

---

## 📊 Features
- **Sales Analysis** – Track daily, monthly, and yearly sales performance.
- **Top Sellers** – Identify the most popular pizzas by quantity and revenue.
- **Inventory Insights** – Monitor ingredient usage and stock requirements.
- **Customer Trends** – Analyze peak order times and popular toppings.
- **Data Visualization Ready** – Query outputs designed for Power BI/Tableau.

---

## 🛠️ Tech Stack
- **Database:** MySQL / PostgreSQL
- **Language:** SQL
- **Tools:** MySQL Workbench / pgAdmin / DBeaver
- **Visualization (Optional):** Power BI / Tableau

---

## 📂 Project Structure

pizza_sales_analytics
├── 📄 schema.sql # Database schema & table creation
├── 📄 data.sql # Sample pizza sales dataset
├── 📄 queries.sql # SQL queries for analysis
├── 📄 visuals.png # Example visualization outputs
└── 📄 README.md # Project documentation


💡 Example Queries
Top 5 Best-Selling Pizzas

SELECT pizza_name, SUM(quantity) AS total_sold
FROM sales
GROUP BY pizza_name
ORDER BY total_sold DESC
LIMIT 5;



---

### 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/pizza-sales-analytics.git
cd pizza-base-analytics


