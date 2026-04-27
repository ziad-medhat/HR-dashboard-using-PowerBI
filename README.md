# HR-Workforce-Distribution-Analytics
An interactive HR Analytics dashboard built in Power BI to track key workforce metrics. This project visualizes employee demographics, performance ratings, and organizational structure to help HR departments make data-driven decisions regarding retention and talent management.

# HR Employee Distribution & Workforce Analytics

## 📌 Project Overview
This project provides a data-driven deep dive into organizational health and workforce demographics. Using a dataset of over 22,000 employee records, I developed an interactive Power BI dashboard to visualize key HR metrics including diversity, geographic distribution, and headcount evolution from 2000 to 2020.

The goal is to help People Operations teams identify representation gaps, track retention through tenure metrics, and understand the shift toward remote work environments.

## 🛠️ Tech Stack
* **Data Visualization:** Microsoft Power BI
* **Data Processing:** Power Query (ETL) & DAX
* **Data Source:** Structured CSV files (Human Resources records)

## 📂 Data Architecture & Files
This repository contains the raw data used to drive the dashboard:
* **`Human Resources.csv`**: The master dataset containing core employee profiles.
* **`employee_change.csv`**: Year-over-year hire and termination trends.
* **`avg_tenure.csv` / `age_length_emp.csv`**: Calculations for length of service.
* **Demographic Files**: `gender.csv`, `race.csv`, `agegroup gender.csv`, and `gender_dept.csv` for intersectional diversity analysis.
* **Geographic Data**: `location.csv` (Headquarters vs. Remote) and state-level distributions.

## 📊 Dashboard Insights & Features
The dashboard is split into high-level distribution and detailed demographic breakdowns:

### 1. Workforce Composition
* **Total Headcount:** Analyzed distribution across **Male (11.3K)**, **Female (10.3K)**, and **Non-Conforming (0.6K)** employees.
* **Diversity Tracking:** Visualization of race distributions, highlighting the representation of White, Black/African American, Asian, and Hispanic/Latino groups.
* **Remote vs. HQ:** A breakdown showing that **75.25%** of the workforce is based at Headquarters, while **24.75%** works Remotely.

### 2. Retention & Growth
* **Average Tenure:** The organization maintains an average employment length of **7.73 years**.
* **Growth Trends:** A time-series analysis from 2000–2020 showing the net change in employee headcount.
* **Age Distribution:** Detailed mapping of age groups (18–64) categorized by gender to identify recruitment trends across generations.

### 3. Geographic Mapping
* Interactive map tracking employees across several states (Ohio, Michigan, Illinois, Indiana, etc.), identifying **Ohio** as the primary hub for the workforce.

## 🚀 How to Use This Project
1. **Explore the Data:** Review the `.csv` files to understand the underlying data structure.
2. **View the Report:** Open `Hr employee report (1).pbix` in Power BI Desktop to interact with the filters.
3. **Reference the PDF:** For a quick look at the static layout, refer to `Hr employee report.pdf`.

---
*Developed as part of a professional Data Analytics portfolio.*
