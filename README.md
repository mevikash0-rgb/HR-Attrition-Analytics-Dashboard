# HR Attrition Analytics Dashboard

## Project Overview
This interactive **HR Attrition Analytics Dashboard** was built in Power BI to analyze employee attrition trends and workforce demographics. The dashboard enables HR professionals and business leaders to monitor key workforce metrics, identify departments and job roles with high attrition, and support data-driven retention strategies.

---

## Dashboard Preview

![HR Attrition Dashboard - Overview](Dashboard_Screenshot_1.png)
![HR Attrition Dashboard - Insights & Recommendations](Dashboard_Screenshot_2.png)

---

## Tools & Technologies

- **SQL (SQL Server)** — Data extraction and staging
- **Power Query** — Data cleaning and transformation
- **Power BI Desktop** — Data modelling and visualization
- **DAX (Data Analysis Expressions)** — Measures and KPI calculations
- **Microsoft Excel** — Supplementary data handling

---

## Project Workflow

The dashboard was built following a structured end-to-end analytics workflow:

**1. Data Extraction (SQL)**
Employee attrition data was first pulled from the HR database using SQL. Queries were used to select relevant fields, filter out irrelevant records, and stage the data before importing it into Power BI.

```SQL
-- Example: Extracting core employee attrition dataset from SQL Server
SELECT
    Employee_ID,
    Age,
    Gender,
    Marital_Status,
    Department,
    JobRole,
    JobLevel,
    JobSatisfaction,
    PercentSalaryHike,
    YearsAtCompany AS Tenure,
    Attrition
FROM dbo.EmployeeAttrition
WHERE EmployeeID IS NOT NULL;
```

**2. Data Cleaning & Transformation (Power Query)**
The SQL-extracted dataset was loaded into Power BI via Power Query, where it was cleaned and shaped — handling nulls, standardising column names, correcting data types, and creating calculated columns needed for analysis (e.g., Tenure buckets, Salary Hike ranges).

**3. Data Modelling**
Relationships were established between fact and dimension tables to support accurate cross-filtering across visuals.

**4. DAX Measures & KPIs**
Key measures such as Attrition Rate %, Average Age, and Average Tenure were built using DAX.

**5. Dashboard Design**
An interactive report was designed with slicers, KPI cards, and visuals to support drill-down analysis by department, job role, gender, and salary hike.

**6. Insights & Recommendations**
A dedicated summary page was built to translate the analysis into actionable HR recommendations.

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---|
| Total Employee Count | 1.47K |
| Active Employees | 237 |
| Attrition Rate (%) | 16% |
| Average Employee Age | 36.92 |
| Average Employee Tenure (Years) | 7.01 |

---

## Dashboard Features

- Employee Count Overview
- Department-wise Attrition Analysis
- Job Role-wise Attrition
- Gender-wise Attrition
- Employee Count by Department
- Salary Hike vs Job Satisfaction Analysis (Matrix View)
- Marital Status Filter (Divorced / Married / Single)
- Job Level Filter
- Dedicated Key Insights & Recommendations page

---

## Skills Demonstrated

- SQL Querying & Data Extraction
- Data Cleaning & Transformation
- Data Modelling
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- HR Analytics
- Business Intelligence
- Data Visualization

---

## Business Insights

- Research & Development has the highest attrition, contributing **133 employees (56.12%)** of total attrition.
- **Laboratory Technicians (62)**, **Sales Executives (57)**, and **Research Scientists (47)** show the highest attrition among job roles.
- Overall employee attrition rate is **16%**.
- **63.29%** of attrition comes from male employees — significantly higher than female attrition.
- Employees with salary hikes in the **11%–13%** range show higher attrition (41 and 23 employees respectively).
- Employees with lower job satisfaction (1–2) show higher attrition across most salary hike ranges.
- Interactive filters allow analysis by Job Level and Marital Status.

---

## Recommendations

- **Focus on High Attrition Departments** — Conduct root cause analysis in Research & Development; implement targeted retention initiatives and monitor progress.
- **Retain Key Job Roles** — Understand pain points of Laboratory Technicians, Sales Executives, and Research Scientists; offer career growth, upskilling, and recognition programs.
- **Review Compensation Strategy** — Benchmark pay for critical roles, ensure market competitiveness, and provide performance-based programs, work-life balance, and mental wellness support.
- **Engage & Support Male Employees** — Understand factors driving male attrition through surveys/exit interviews; introduce engagement and wellness programs.
- **Improve Job Satisfaction** — Run regular engagement surveys, act on feedback, and build a culture of trust, growth, and inclusivity.

---

## Project Files

- `Employee_Attrition_Dashboard.pbix`
- `Dashboard_recorded_video.mp4`
- `Dashboard_Screenshot_1.png`
- `Dashboard_Screenshot_2.png`
- `README.md`

---

## AI Assistance

Artificial Intelligence (AI) was used to enhance the visual design of this dashboard by generating custom icons used within the report. AI was used solely as a design aid to improve the dashboard's visual appeal.

---

## Project Highlights

- Extracted and staged HR data using SQL before transformation in Power Query.
- Built an interactive HR Analytics dashboard using Power BI.
- Created DAX measures and KPIs to analyze employee attrition.
- Designed an intuitive, interactive report with slicers and visualizations.
- Enhanced the dashboard's visual appeal using AI-generated icons.

---

## Author

**Vikash Bhagat**
Senior Quality Assurance & Analyst | Power BI | SQL | Advanced Excel | HR Analytics | Data Analytics