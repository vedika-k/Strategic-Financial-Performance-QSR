# 📊 Strategic & Financial Performance Dashboard  
**McDonald’s vs Burger King (2021–2023)**  

An interactive **Power BI dashboard** designed to compare McDonald’s and Burger King across revenue, expenses, store growth, and regional performance. This project demonstrates how **data modeling, DAX, Power Query, and visualization** can provide actionable insights into the competitive dynamics of the Quick Service Restaurant (QSR) industry.  

---

## 🎯 Project Overview  
This project delivers a **15-insight Power BI dashboard** with dynamic interactivity and executive-focused storytelling.  

- **KPI Row** – Track McD vs BK revenue, system-wide sales, and store count  
- **Revenue Analysis** – Compare revenue trends, indexed growth (2021=100), and expense breakdown  
- **Growth Insights** – Explore Burger King’s comparable sales growth %, store evolution, and system-wide sales  
- **Regional Analysis** – Revenue heatmap by region, YoY growth bars, and top McDonald’s regional performers  

---

## 🧰 Tools & Technologies Used  
- **Python (pandas, numpy)** – Data cleaning, schema standardization, preprocessing  
- **Excel** – Initial data formatting and exploration  
- **Power Query (M)** – ETL, data type management, shaping in Power BI  
- **Power BI** – Dashboard design, KPI cards, slicers, formatting  
- **DAX** – Custom measures (YoY%, indexed revenue, brand-specific KPIs)  

---

## 📊 Dashboard Features  

### 🔑 Key Features  
- **KPI Overview** – McD revenue, BK revenue, BK system-wide sales, BK store count  
- **Revenue Trends** – Year-over-year line chart comparisons (2021–2023)  
- **Expense Analysis** – Multi-line breakdown of McD operating vs franchise expenses  
- **Regional Performance** – Matrix & heatmap for revenue by brand & region  
- **Growth Metrics** – Indexed revenue (2021=100), YoY % change, comparable sales %  

### 🛠️ Interactivity  
- **Dynamic Filters** – Dropdown slicers for Year, Brand, Metric  
- **Cross-Comparison** – Side-by-side visuals for McD vs BK performance  
- **Data Storytelling** – Layout flows from KPI summary → trend analysis → regional deep dive  

---

## 📂 File Structure  
```
project/
├── data/
│ ├── mcd.csv                      # Raw McDonald’s data
│ ├── bk.csv                       # Raw Burger King data
│ └── qsr_standardized.csv         # Cleaned & standardized schema
├── powerbi/
│ └── Strategic_Financial_Performance_Dashboard.pbix
├── docs/
│ ├── dashboard_screenshots/       # PNGs of the dashboard
│ └── QSR_Dashboard_Report.pdf     # Exported report
└── README.md                      # Project documentation

```
