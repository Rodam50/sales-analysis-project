# 📊 Sales Data Analysis Project

> A complete end-to-end data analysis project using **Python** and **SQL** to extract business insights from 1,000+ sales transactions across 2023–2024.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![SQLite](https://img.shields.io/badge/SQL-SQLite-orange?logo=sqlite)
![pandas](https://img.shields.io/badge/pandas-2.0-green?logo=pandas)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 🗂️ Project Structure

```
sales_analysis_project/
│
├── data/
│   └── sales_data.csv          # 1,000 generated sales transactions
│
├── scripts/
│   ├── generate_data.py        # Generates the synthetic sales dataset
│   └── analyze_sales.py        # Full Python analysis + visualizations
│
├── sql/
│   ├── analysis_queries.sql    # 10 SQL queries with explanations
│   └── run_queries.py          # Runs SQL queries via Python + SQLite
│
├── outputs/
│   └── sales_dashboard.png     # Auto-generated charts
│
└── README.md
```

---

## 🎯 Business Questions Answered

| # | Question | Tool |
|---|----------|------|
| 1 | What is our overall revenue, orders, and units sold? | SQL + Python |
| 2 | Which product category drives the most revenue? | SQL + Python |
| 3 | What are our top 5 best-selling products? | SQL + Python |
| 4 | How does revenue trend month by month? | SQL + Python |
| 5 | Which region performs best? | SQL + Python |
| 6 | Who are the top sales representatives? | SQL + Python |
| 7 | How did 2024 compare to 2023? (YoY growth) | SQL |
| 8 | Do discounts actually help sales volume? | SQL |
| 9 | What was the best month for each region? | SQL (Window Functions) |
| 10 | Which individual orders were exceptionally large? | SQL |

---

## 📈 Key Findings

- **Total Revenue**: $2,154,407 across 1,000 orders
- **Top Category**: Electronics (64.4% of all revenue)
- **Best Product**: Laptop Pro — $887,739 in revenue
- **Top Region**: West — $515,970 total revenue
- **Top Sales Rep**: Alice Nakamura — $267,473 total
- **YoY Growth**: Revenue grew from 2023 → 2024

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3** | Data loading, cleaning, analysis |
| **pandas** | Data manipulation and aggregation |
| **matplotlib / seaborn** | Data visualizations |
| **SQL (SQLite)** | Querying and aggregating data |
| **sqlite3** | In-memory SQL engine via Python |

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/sales-analysis-project.git
cd sales-analysis-project
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Generate the dataset
```bash
python scripts/generate_data.py
```

### 4. Run the Python analysis
```bash
python scripts/analyze_sales.py
```

### 5. Run the SQL queries
```bash
python sql/run_queries.py
```

---

## 📊 Dashboard Preview

The analysis script auto-generates a 4-panel dashboard:

- 📈 **Monthly Revenue Trend** — line chart over 24 months  
- 📦 **Revenue by Category** — bar chart with value labels  
- 🏆 **Top 5 Products** — horizontal bar chart  
- 🌍 **Revenue by Region** — pie chart with percentages  

---

## 🧠 Skills Demonstrated

- ✅ Data generation and CSV handling
- ✅ Data cleaning and type conversion with pandas
- ✅ Aggregation, grouping, and filtering
- ✅ SQL joins, window functions (`RANK() OVER`), subqueries
- ✅ Year-over-year comparisons
- ✅ Data visualization with matplotlib & seaborn
- ✅ Writing clean, well-documented Python code

---

## 📄 License

MIT — free to use, fork, and build on.

---

*Built as a portfolio project to demonstrate Python and SQL data analysis skills.*
