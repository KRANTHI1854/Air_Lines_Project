# ✈️ High Cloud Airlines — Multi-Tool Data Analytics Project  

## 📘 Project Overview  
The **High Cloud Airlines Analytics Project** explores airline performance metrics such as **load factors, passenger trends, carrier efficiency, and route performance**.  
What makes this project unique is that **the same business questions were solved independently using four major analytical tools — Excel, SQL, Power BI, and Tableau.**

> 🧠 Goal: To demonstrate analytical capability across multiple platforms using one dataset and identical problem statements.

---

## 🧩 Tools & Technologies Used  

| Tool | Purpose | Description |
|------|----------|-------------|
| **Excel** | Data Cleaning & Analysis | Solved KPIs using formulas, pivot tables, and charts |
| **SQL (MySQL)** | Query-Based Analysis | Wrote structured SQL queries for the same business insights |
| **Power BI** | Dashboard & KPI Visuals | Designed interactive dashboards for the same questions |
| **Tableau** | Visual Storytelling | Built story dashboards showing identical insights visually |

---

## 🪄 Project Philosophy — “Same Questions, Different Tools”  
Each tool was used to solve **the same analytical objectives**, such as:
- Creating date fields and time-based metrics  
- Calculating load factor (passengers vs seats)  
- Analyzing top carriers and routes  
- Studying weekday vs weekend flight performance  
- Examining quarterly and yearly trends  

By solving these same problems in multiple environments, this project demonstrates **tool versatility**, **analytical consistency**, and **cross-platform adaptability**.

---

## 🧹 **Excel Module — Data Cleaning & KPI Analysis**
**File:** `Excel High_cloud_Airlines_Project.xlsx`

### Key Steps:
- Cleaned and formatted raw data (removed nulls, blanks, inconsistencies).  
- Created **Flight Date** from *Year, Month, Day* using formulas.  
- Used pivot tables to calculate:
  - **Monthly / Quarterly / Yearly Load Factor**
  - **Top Carriers by Passengers**
  - **Top 10 Routes (From–To City)**
  - **Weekend vs Weekday Traffic**
  - **Flights by Distance Group**
- Applied **conditional formatting** to highlight trends.  
- Presented insights using Excel charts and dashboards.

---

## 🧮 **SQL Module — Query-Based Analysis**
**File:** `High Cloud Airline.sql`

### Database Used:
`Airline`

### Key SQL Components:
- Created `FlightDate` using `STR_TO_DATE(CONCAT(Year, '-', Month, '-', Day))`.  
- Used **CTEs, date functions, and aggregation** to replicate Excel logic.  

### Main Insights Solved:
1. **Monthly Load Factor**  
2. **Quarterly Load Factor**  
3. **Yearly Load Factor**  
4. **Load Factor by Carrier Name**  
5. **Top 10 Carriers by Passengers**  
6. **Top Routes (From–To City)**  
7. **Weekend vs Weekday Load Factor**  
8. **Flights by Distance Group**

> ✅ The SQL module validates the same KPIs solved in Excel — but through coding and query logic.

---

## 📊 **Power BI Module — Interactive Dashboards**
**File:** `Power BI High_cloud_Airlines_Project.pbix`

### Highlights:
- Imported the same dataset used in Excel and SQL.  
- Created calculated fields using **DAX measures** replicating SQL logic:
  - `Load Factor % = SUM(Transported Passengers) / SUM(Available Seats)`
  - `Weekend/Weekday Split`
  - `Quarterly Load Trends`
- Designed interactive visuals for:
  - **Top Carriers & Routes**
  - **Load Factor by Month/Year**
  - **Distance Group Analysis**
  - **Passenger vs Seat Utilization**
- Built an **Executive Summary Page** showing all KPIs visually.
- Added **filters and slicers** for year, carrier, and region.

---

## 📈 **Tableau Module — Storytelling Dashboards**
**File:** `Tableau High_Cloud_Airlines_Project.twbx`

### Key Story Points:
- Connected the same dataset for consistency.  
- Recreated identical KPIs from Excel/SQL using Tableau calculated fields.  
- Visualized:
  - **Load Factor Trends (Monthly & Quarterly)**
  - **Top 10 Carriers by Passenger Count**
  - **Top Routes by Flights**
  - **Weekend vs Weekday Load Factor**
  - **Distance Group Distribution**
- Built an **executive story dashboard** combining all key visuals for presentation.

---

## 📌 Core Business Insights (from all four tools)
- **Load Factor increased gradually** across quarters, showing improved seat utilization.  
- **Top 5 Carriers** handled a majority of total passengers.  
- **Short and medium-distance routes** carried most of the traffic.  
- **Weekend flights** had slightly higher occupancy compared to weekdays.  
- Certain **long-distance routes** showed underperformance, revealing optimization opportunities.

---

## 🧭 Learnings & Takeaways
- Practiced solving **identical analytical questions** using four different platforms.  
- Improved understanding of how KPIs are calculated across tools.  
- Strengthened skills in **data cleaning, transformation, visualization, and storytelling**.  
- Learned to maintain consistency in analytical logic across diverse technologies.

---

## 🗂️ Repository Structure
📁 High_Cloud_Airlines_Project/
├── 📊 Excel High_cloud_Airlines_Project.xlsx
├── 🧮 High Cloud Airline.sql
├── 📈 Power BI High_cloud_Airlines_Project.pbix
├── 📉 Tableau High_Cloud_Airlines_Project.twbx
└── 📘 README.md

