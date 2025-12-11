# HR Analytics Dashboard: Employee Attrition Analysis

### 1. Project Title / Headline
**HR Attrition Analysis Dashboard: Workforce Retention & Turnover Insights**

A strategic Power BI dashboard designed to analyze employee turnover, identifying key patterns in attrition based on demographics, job roles, and compensation to drive better retention strategies.

### 2. Short Description / Purpose
This "Attrition Analysis" dashboard provides a comprehensive overview of the workforce status, specifically focusing on employees leaving the organization. It enables HR managers to pinpoint high-risk areas by visualizing attrition across various dimensions such as age groups, education fields, and salary slabs. The tool transforms raw HR data into clear metrics to support data-driven decision-making for reducing turnover.

### 3. Tech Stack
The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – The primary tool for creating the interactive dashboard and visualizations.
* ⚙️ **Power Query** – Utilized for data cleaning and transformation to ensure accuracy in the "Attrition by Education" and "Job Role" categorizations.
* 🧮 **DAX (Data Analysis Expressions)** – Used to calculate dynamic Key Performance Indicators (KPIs) such as "Attrition Rate (16.1%)" and "Average Salary (6503)".
* 📉 **Data Modeling** – Structured relationships to allow slicing by departments (Human Resources, R&D, Sales).

### 4. Data Source
The dashboard analyzes a dataset of **1,470 employee records**.

* **Dataset Structure:** The data includes fields for:
    * **Demographics:** Gender (Male/Female), Age Groups, Marital Status.
    * **Professional Details:** Job Role, Department, Education Field, Years at Company.
    * **Compensation:** Monthly Salary (analyzed in slabs like "Upto 5k", "5k-10k").
    * **Attrition Status:** Binary classification (Yes/No) of employees who have left.

### 5. Features / Highlights

* **Business Problem**
    High employee turnover increases recruitment costs and leads to a loss of organizational knowledge. Without granular visibility into *who* is leaving and *why*, HR departments cannot formulate effective retention strategies.

* **Goal of the Dashboard**
    To identify the root causes of attrition by correlating turnover with factors like salary, age, and job role, ultimately aiming to lower the current **16.1% attrition rate**.

* **Walk Through of Key Visuals**
    * **Top-Level KPIs:** Immediate view of vital stats including Total Employees (1,470), Total Attrition (237), Average Age (37), and Average Years at Company (7.01).
    * **Attrition by Age Group:** A column chart highlighting that the **26-35 age group** has the highest attrition (116 employees).
    * **Education & Gender Analysis:** A Donut chart showing "Life Sciences" (37.55%) as the primary education field for leavers, and a Treemap comparing Male vs. Female attrition.
    * **Salary Insights:** A bar chart revealing a strong correlation between lower income and attrition, with **163 employees** leaving in the "Upto 5k" salary slab.
    * **Role-Based Analysis:** A breakdown showing specific roles like "Laboratory Technician" and "Sales Executive" have the highest turnover counts.

* **Business Impact & Insights**
    This dashboard reveals that attrition is highest among younger employees (18-35) and those in lower salary brackets. By targeting these specific demographics with career development programs or salary adjustments, the organization can proactively address the 237 recorded exits.
