# ✈️ Airline Data Analytics Platform  
**Final Project – Data Lab Academy (Coders Lab)**

## 🧠 Project Summary

This project is a **full end-to-end data analytics solution** built as the final assignment of the **Data Lab Academy at Coders Lab**.  
It represents my **first large-scale data project**, developed collaboratively in a team of four, covering the complete data lifecycle:

**API ingestion → database storage → analysis → visualization → interactive dashboard**

The goal was to **replace manual, error-prone analytics processes** with an **automated, scalable data pipeline** based on real-world airline data.

---

## 🎯 Business Context

The simulated client operated in the **airline industry** and relied heavily on:
- manual data collection
- spreadsheet-based analysis
- limited external reporting tools

These constraints resulted in:
- delayed insights
- inconsistent data
- lack of automation

Our task was to **design and implement an automated data analytics platform** that:
- integrates multiple data sources
- stores structured data in a relational database
- enables analytical exploration
- provides clear visual insights for decision-making

---

## 🏗️ Architecture Overview

```
External APIs
   ↓
Python (Requests, JSON)
   ↓
Data Processing (Pandas, NumPy)
   ↓
PostgreSQL (SQLAlchemy, psycopg2)
   ↓
Analytics & Aggregations (SQL + Pandas)
   ↓
Interactive Dashboard (Plotly + Dash)
```

---

## 🔧 Tech Stack

**Languages & Tools**
- Python
- SQL
- PostgreSQL

**Libraries & Frameworks**
- requests, json, time
- pandas, numpy
- threading
- psycopg2, sqlalchemy
- plotly.express, plotly.io
- dash

---

## 🧩 Team Responsibilities (Role-Based Approach)

### Data Engineer
- Integrated external API services
- Automated data ingestion
- Designed database schema
- Loaded and maintained data in PostgreSQL

### Data Analyst
- Explored airline, airport, flight, and weather data
- Identified key operational patterns and anomalies
- Performed aggregations and KPI calculations

### BI Developer
- Built interactive visualizations
- Designed dashboards for business users
- Translated analytical results into actionable insights

---

## 📊 Dataset Scope

The dataset covered multiple domains within the airline industry:
- flights and routes
- airports
- weather conditions
- operational performance indicators

This enabled cross-domain analysis and deeper insight discovery.

---

## 🚀 Key Outcomes

- Automated data ingestion from external APIs  
- Centralized PostgreSQL database  
- Reproducible analytics workflow  
- Interactive Dash-based dashboard  
- Significant reduction of manual processing  

---

## 📚 What This Project Demonstrates

- End-to-end data pipeline design
- Practical SQL and relational modeling
- Python-based ETL processes
- Business-focused analytics
- Team collaboration in a data project

---

## 🔮 Future Improvements

- Scheduling & orchestration (Airflow / cron)
- Cloud deployment (AWS / GCP)
- Data quality validation
- Dimensional modeling (star schema)
- Access-controlled dashboards

---

## 🏁 Final Notes

This project marked the transition from **learning individual tools** to **building complete data solutions**, forming a strong foundation for further work in **Data Engineering and Analytics**.
