# SF Muni Transit Reliability Analysis  
**SF Muni Transit Recovery & Resource Reallocation (Post-COVID)**

> A system-level transit reliability analysis focusing on post-COVID demand recovery and resource reallocation decisions for San Francisco Muni.

📍 **City:** San Francisco  
🚌 **System:** San Francisco Municipal Transportation Agency (Muni)  
📅 **Period:** 2011–2025  
🛠 **Tools:** SQL (BigQuery), Python, Looker Studio, Excel  
👥 **Project Type:** Team Project (Le Wagon Data Analytics Bootcamp)

---

## Business Context

As San Francisco emerges from COVID-19, public transit demand patterns have changed significantly.  
Rather than simply adding more vehicles or budget, the city faces a key challenge:

**How can existing transit resources be reallocated more effectively to improve reliability and rider experience?**

This project evaluates system-wide and route-level performance to support data-driven transit planning decisions.

---

## Key Business Questions

1. Has overall transit demand recovered to pre-COVID levels?
2. Are current resources aligned with route-level demand and pressure?
3. Which routes consistently underperform in terms of reliability?
4. Where can targeted reallocation improve system efficiency and service regularity?

---

## Analytical Approach

We combined **system-level** and **route-level** analysis across multiple dimensions:

- **Demand Recovery Analysis**
  - Compared post-COVID ridership to 2019 baseline
  - Identified under- and over-recovered routes

- **Demand-to-Supply & Pressure Analysis**
  - Built demand-to-supply ratios by route and time period
  - Designed a **Pressure Score** to classify routes into high / medium / low pressure
  - Compared weekday vs weekend service gaps

- **Reliability & On-Time Performance**
  - Analyzed on-time, early, and late arrival distributions
  - Evaluated service regularity across route types and time slots

- **Forecasting & Strategic Planning**
  - Forecasted weekday boardings through 2026
  - Assessed whether additional resources are truly required

---

## Dashboard Highlights

### 1️⃣ System Reliability Overview & Route Performance

This view provides a **system-wide reliability snapshot**, combining trend analysis with route-level comparisons.

![System Reliability Overview](System%20Reliability%20Overview.png)

**Key elements include:**
- Overall on-time rate, late arrival rate, and average delay
- Monthly reliability trends
- Best- and worst-performing routes
- Route type × time slot on-time heatmap

---

### 2️⃣ Resource Pressure & Allocation Insights

This view highlights **misalignment between demand and supply**, helping identify where resources should be reallocated.

![Resource Pressure Analysis](Resource%20Pressure%20Analysis.png)

**Key elements include:**
- Route-level pressure classification (high / medium / low)
- Demand-to-supply comparison across routes
- Identification of structurally over- and under-served routes

---

## Key Insights

- Overall ridership has largely recovered, but **recovery is uneven across routes**
- The system appears to have **sufficient total resources**, but allocation is misaligned with demand
- Some routes consistently operate under **high pressure**, while others are underutilized
- Cable car routes show the **lowest on-time performance**
- High levels of early arrivals reduce service regularity
- **Late arrivals negatively impact rider experience more than early arrivals**

---

## Strategic Recommendations

1. Reduce service on routes that remain **40%+ below** the 2019 ridership baseline  
2. Reallocate vehicles and frequency from **low-pressure** routes to **high-pressure** routes  
3. Reduce early arrivals to improve service regularity and stabilize wait times  
4. Base capital investment decisions on **long-term demand forecasts**, not short-term recovery trends  

---

## Interactive Dashboard

🔗 **Looker Studio Dashboard (Team Project):**  
https://lookerstudio.google.com/reporting/45a126c0-81d1-462b-8edf-7d3318792e89

> Note: Additional exploratory analyses (including recovery vs 2019 baseline by route) are available within the interactive dashboard.

---

## Project Assets

- Interactive dashboards (Looker Studio)
- SQL queries and analytical logic (BigQuery)
- Data modeling and transformations
- Presentation storytelling embedded within the dashboard

---

## Contact

- **LinkedIn:** https://www.linkedin.com/in/ling-li-data
