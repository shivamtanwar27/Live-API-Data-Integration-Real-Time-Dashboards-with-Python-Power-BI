# Live-API-Data-Integration-Real-Time-Dashboards-with-Python-Power-BI


 
Refreshable Power BI dashboard that ingests ~26 World Bank indicators for 200+ countries via a Python pipeline. Provides cards, bar charts and trend charts to compare countries, view top/bottom performers and monitor socio-economic indicators. Built to enable daily refreshes and reduce manual update time by ~80%.

---

##  Overview
This project demonstrates an end-to-end pipeline: automated data ingestion from the World Bank API → data cleaning & transformation in Python → persistent storage (CSV) → interactive visualizations in Power BI. The goal is reproducible, updatable dashboards for policy/stakeholder reporting.



---

##  Objectives / Questions the Dashboard Answers
1. Understand overall economic & social landscape (GDP per capita, growth rate, trade, forest area, etc.)  
2. Compare health spending patterns across regions (health spending as % of GDP).  
3. Analyze trends over time for critical socio-economic indicators.  
4. Evaluate relationship between internet access and immunization/health outcomes.  
5. Assess internet access impact on unemployment.  
6. Identify underperforming countries in poverty reduction (bottom N) and top performers.  
7. Examine interrelationships among health indicators (expenditure, life expectancy, immunization).  
8. Explore whether increased health spending correlates with improvements in life expectancy.

---

## Tech Stack
- Python (pandas, requests)  
- Power BI Desktop 

---

##  Data Source
- [World Bank API](https://data.worldbank.org/) — public indicators (no API key required).  
  Example indicator codes: `NY.GDP.PCAP.CD` (GDP per capita), `SH.XPD.CHEX.GD.ZS` (health expenditure % of GDP), etc.


