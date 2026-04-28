# HR-Workforce-Distribution-Analytics
An interactive HR Analytics dashboard built in Power BI to track key workforce metrics. This project visualizes employee demographics, performance ratings, and organizational structure to help HR departments make data-driven decisions regarding retention and talent management.


# HR Workforce Analytics & Diversity Insights (2000 - 2020)

## 📌 Project Overview
This project is a comprehensive **Human Resources Data Analytics** solution developed to provide a 360-degree view of a company's workforce. Analyzing over **22,000 employee records**, I built an interactive Power BI dashboard that transforms raw HR logs into actionable insights regarding diversity, geographic distribution, and employee retention.

The primary objective is to equip People Operations teams with the data needed to identify representation gaps, analyze headcount growth, and monitor the average length of employment across departments.

---

## 📊 Detailed Dashboard Analysis
The analysis is structured into two main report pages, each focusing on critical HR pillars:

### 1. Workforce Distribution & Diversity
* **Headcount Totals:** Total workforce analyzed consists of **11,288 Male**, **10,321 Female**, and **605 Non-Conforming** employees.
* **Ethnic Representation:** Deep-dive into racial distribution:
    * **White:** 6,328 employees
    * **Two or More Races:** 3,648 employees
    * **Black or African American:** 3,619 employees
    * **Asian:** 3,562 employees
    * **Hispanic or Latino:** 2,501 employees
* **Location Metrics:** **75.25% (16,715)** of employees are based at **Headquarters**, while **24.75% (5,499)** work **Remotely**.
* **Geographic Spread:** Visualized workforce density across the Midwest, identifying **Ohio** as the primary talent hub.

### 2. Retention & Recruitment Trends
* **Average Tenure:** The company maintains a healthy average employment length of **7.73 years**.
* **Age Demographics:** Data mapping across age brackets shows a strong presence in the **25-54** range, with specific gender breakdowns for each group (e.g., 3,129 males in the 35-44 bracket).
* **Historical Growth:** Tracking the **Net Change** from 2000 to 2020, showing a steady climb in headcount with a significant hiring surge identified in the 2010s.

---

## 🛠️ Tech Stack & Methodology
* **Visualization:** Microsoft Power BI
* **ETL & Data Modeling:** Power Query (used for cleaning date formats, handling null termination dates, and calculating ages).
* **DAX Formulas:** Developed custom measures for:
    * **Total Active Employees** (Filtering out terminated records).
    * **Net Change %** (Year-over-Year headcount growth).
    * **Average Tenure** (DATEDIFF logic between hire and termination/current date).
* **Data Sources:** 10+ CSV files covering gender, race, department, job titles, and location.

---

## 📂 Data Architecture
The repository includes the following structured data files:
* `Human Resources.csv`: Master file with names, hire dates, and job titles.
* `employee_change.csv`: Yearly hire/termination net change logic.
* `avg_tenure.csv`: Pre-calculated tenure averages by department.
* `gender_dept.csv`: Intersectional data for gender representation across units.
* `age_length_emp.csv`: Core data for age-based retention analysis.

---

## 📈 Visual Documentation

### I. Workforce Composition & Diversity
*Highlights the high-level distribution of gender, race, and location.*
![Workforce Distribution](Screenshot%202026-04-28%20031817.png)

### II. Age & Demographic Breakdown
*Detailed view of age groups and historical headcount evolution.*
![Age Distribution](Screenshot%202026-04-28%20031833.png)

---

## 🚀 How to Explore This Project
1. **PBIX File:** Download and open `Hr employee report (1).pbix` to interact with the slicers and drill down into specific departments (e.g., Engineering vs. Sales).
2. **CSV Datasets:** Review the CSV files to see the raw data structure before Power Query transformations.
3. **PDF Summary:** See `Hr employee report.pdf` for a static snapshot of the insights.


