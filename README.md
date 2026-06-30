# HR Analytics Dashboard | Python & Power BI

**Advanced Data Visualization Project** ---

## 📋 Project Overview

This project analyzes employee data to provide comprehensive insights into workforce trends, hiring quality, turnover rates, and demographic distributions using Power BI and Python.

📌 Note: The dataset used in this project is mock/dummy data created for demonstration and portfolio purposes only. The metrics do not represent any real-world company.

## 🛠️ Tech Stack & Tools
* **Data Cleaning & Preprocessing:** Python (`pandas`, `numpy` via Jupyter Notebooks)
* **Data Visualization & Analytics:** Power BI (DAX, Power Query)
* **Data Source:** Excel

---

## 🖼️ Dashboards & Insights

### 1. Main Dashboard
![Main Dashboard](images/dashboard.png)

**Key Metrics:**
- **32K** Active Employees
- **40** Average Age
- **42K** Bad Hires 
---

### 2. New Hires Analysis
![New Hires](images/newhires.png)

- New hires trends by month and employment type (Full-time / Part-time).
- Bad hire ratio by region to optimize recruitment sources.
- Gender and regional distribution of new talents.

---

### 3. Active Employees
![Actives](images/actives.png)

- Active employees distribution by region, gender, and age groups.
- Monthly workforce growth trends.
- In-depth analysis of separation reasons to improve retention.

---

### 4. Bad Hires Analysis
![Bad Hires](images/badhires.png)

- Comparative analysis: Bad hires vs. New hires by region.
- Bad hires distribution by month, age group, ethnicity, and gender to identify potential hiring bottlenecks.

---

## 📁 Project Structure

```bash
HR-Analytics-PowerBI/
├── data/
│   ├── Data.xlsx
│   └── Data_Cleaned_Final.xlsx
├── notebooks/
│   └── HR_Data_Cleaning.ipynb
├── powerbi/
│   └── HR_Analytics.pbix
├── images/
│   ├── dashboard.png
│   ├── newhires.png
│   ├── actives.png
│   └── badhires.png
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE