# Layoff Trends Analysis Dashboard (2020–2023)-Power-BI-SQL-Project

This project analyzes global tech layoffs between 2020 and 2023 using Power BI and SQL to identify key patterns and mismanagement signals. The dashboard is designed for executive-level decision-making by investors, HR leaders, and market analysts.

Live dashboard- https://app.powerbi.com/links/CE3C1V7WyK?ctid=dba738f5-614b-48bf-af08-525b5cba2b1e&pbi_source=linkShare

---

## 📑 Table of Contents

- [Overview](#overview)
- [Project Description](#project-description)
- [Data](#data)
- [Methodology](#methodology)
- [Analysis and Findings](#analysis-and-findings)
- [Recommendations](#recommendations)
- [Visualizations](#visualizations)
- [Files and Resources](#files-and-resources)
- [Conclusion](#conclusion)
- [Contact Information](#contact-information)

---

## 🧠 Overview

The goal of this project was to uncover layoff patterns in the global tech industry post-COVID and quantify their severity relative to funding raised, industries, and funding stages.

---

## 📊 Project Description

### 🔍 Background

From 2020 to 2023, several tech companies across the globe executed mass layoffs. The dataset included key indicators such as total employees, laid-off count, industry, company stage, and capital raised.

### 🎯 Objective

- Quantify layoff severity using a custom Layoff Impact% metric
- Identify patterns across funding stages (e.g., Seed, Series A–D, IPO)
- Highlight signs of mismanagement through comparative insights

---

## 📂 Data

### 🔗 Data Source

The dataset was taken from Kaggle, cleaned using SQL for smooth analysis in Power BI.

### 🧾 Data Description

Fields include:
company, location, industry,	total_laid_off,	percentage_laid_off,	date,	stage,	country, funds_raised_millions
---

## ⚙️ Methodology

### 🧼 Data Cleaning (SQL)

- 
- Removed duplicate records
- Standardized text and date formats
- Handled null values and missing employee data
- Merged multiple tables to build relational models

### 🛠️ Tools & Technologies

- **SQL** for ETL and data preparation
- **Power BI** for data visualization and DAX modeling
- **Excel** for initial sanity checks

---

## 📈 Analysis and Findings

### 🌐 Geography & Industry Insights

- U.S. dominates layoffs, especially in the tech and finance sectors.
- Industries like Crypto and SaaS show volatile layoff trends.

### 💰 Funding Stage vs. Layoff Severity

- Higher layoff impact in **Series D+** and **Post-IPO** companies.
- Indicates potential overfunding and poor workforce planning.

### 📉 Layoff Impact Metric

- Defined as: `(Laid Off / Total Fund raised) * 100`
- Companies with a Layoff Impact% > 50% are likely dealing with severe mismanagement.

---

## 💡 Recommendations

- **For Investors**: Scrutinize late-stage startups with high Layoff Impact % before further funding.
- **For HR/Workforce Planning**: Plan hiring phases based on capital burn rates and funding maturity.
- **For Analysts**: Use Layoff Impact % as a red flag metric in risk assessments.

---

## 📊 Visualizations

- KPI Cards: Total Layoffs, Companies Affected
- Bubble Chart: Layoffs Severity vs Capital Raised (bubble size = layoffs)
- Bar Chart: Top 3 industries by layoffs and Top 3 countries by layoffs

👉 Dashboard -- https://app.powerbi.com/links/CE3C1V7WyK?ctid=dba738f5-614b-48bf-af08-525b5cba2b1e&pbi_source=linkShare

---
## ✅ Conclusion

This dashboard offers, how layoffs correlate with funding rounds, geography, and industry verticals. It aids decision-makers in identifying early warning signs and better planning workforce strategies.

---

## 📬 Contact Information

👤 **Abhishek Kushwaha**  
📩 [LinkedIn](www.linkedin.com/in/abhishek-kushwaha-0a349125b)   
📧 abhishek.ak1808@email.com  


