![Banner](README%20image.png)

# 🏡 Smart Home Pricing Analytics

A comprehensive, end-to-end data analytics project featuring advanced data cleaning, relational data modeling, rigorous KPI calculations, and multi-page interactive executive dashboards for real estate pricing and smart home features.

---

## 🚀 Project Overview
This repository showcases an end-to-end data analytics workflow designed to transform raw housing market data and smart home valuation metrics into actionable strategic insights. The solution covers the entire data lifecycle—from ingestion, cleaning, and transformation using SQL and Python, to enterprise-grade data modeling and visualization.

---

## 🛠️ Tech Stack & Tools
- **Data Processing & Transformation:** Python (Pandas, NumPy), SQL Server / MySQL
- **Data Modeling:** Relational Star Schema, Power Pivot, DAX
- **Data Visualization & Dashboards:** Power BI, Tableau, Streamlit
- **Design & Layout Mockups:** Figma, Visily

---

## 📸 Dashboard & Interface Showcase

### 1. Home Page / Landing View
The entry point of the analytics application, designed for seamless navigation and high-level metric summaries of smart home pricing trends.

![Home Page](Home%20Page.png)

---

### 2. Executive Dashboard - Overview & KPIs (Dashboard 1)
High-level operational performance metrics, median housing prices, smart feature premiums, and core KPI scorecards.

![Dashboard 1](Dashboard%201.png)

---

### 3. Detailed Performance Analysis (Dashboard 2)
Deep-dive analytical views highlighting regional price distributions, feature correlations, and comparative valuation indicators.

![Dashboard 2](Dashboard%202.png)

---

### 4. Behavioral & Operational Insights (Dashboard 3)
Granular exploration of buyer preferences, smart technology adoption rates, and transactional valuation patterns.

![Dashboard 3](Dashboard%203.png)

---

### 5. Advanced Forecasting & Strategic Summary (Dashboard 4)
Predictive price trends, market demand benchmarks, and executive recommendations based on historical smart home pricing data.

![Dashboard 4](Dashboard%204.png)

---

## 📖 Detailed Project Documentation & Methodology

### 1. Data Ingestion & Preparation Workflow
The project initiates with raw real estate datasets containing over 79 property attributes (including structural size, geographical zoning, remodeling history, and specific smart home amenities). Initial steps involved importing raw CSV files into Python and SQL environments, auditing missing values, handling data types, and treating extreme statistical outliers to ensure high analytical fidelity.

### 2. Relational Modeling & Database Architecture
To optimize analytical query performance, a robust relational star-schema architecture was designed. Fact tables containing transactional sale prices and timestamps were linked to normalized dimension tables representing neighborhoods, property types, zoning categories, and internal/external features. This setup enables lightning-fast cross-filtering and dynamic slice-and-dice reporting across all dashboard views.

### 3. Advanced Calculations & KPI Engineering
Using advanced DAX measures and SQL aggregate functions, several critical performance indicators and business metrics were calculated:
- **Price per Square Foot:** Evaluating unit land and construction efficiency across various neighborhoods.
- **Smart Feature Valuation Premium:** Quantifying the exact monetary appreciation added by smart home integrations, fireplaces, high-grade kitchens, and garage capacities.
- **Year-over-Year Growth:** Tracking macroeconomic valuation shifts and historical price trajectories over multi-year periods.

### 4. User-Centric Dashboard Design & Deployment
Before implementing the final interfaces in Power BI and Tableau, wireframes and structural mockups were custom-designed in Figma and Visily. This guaranteed an intuitive user experience featuring distinct navigation zones, cohesive color theory, and responsive multi-page views tailored for executive decision-makers.
