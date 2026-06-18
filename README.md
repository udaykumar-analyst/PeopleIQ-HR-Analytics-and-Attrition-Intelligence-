# HR Analytics & Employee Attrition Intelligence Dashboard

## 📌 Project Overview

This project is an interactive HR Analytics Dashboard developed using Power BI to analyze employee attrition trends and workforce demographics. The dashboard provides valuable insights into employee turnover patterns, helping HR teams identify key areas that require attention and improve employee retention strategies.

The dashboard enables users to explore attrition data through interactive visualizations and filters, making it easier to understand workforce behavior across different departments, job roles, age groups, genders, and business travel categories.

---

## 🎯 Business Problem

Employee attrition is one of the major challenges faced by organizations. High attrition rates can lead to increased recruitment costs, productivity loss, and disruption in business operations.

The goal of this dashboard is to:

- Analyze employee attrition patterns.
- Identify departments with high employee turnover.
- Understand the impact of age, gender, job role, and business travel on attrition.
- Support HR teams in making data-driven decisions.
- Improve employee retention strategies.

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|------|--------|
| Total Employees | 1000 |
| Average Salary | 6.50K |
| Average Age | 36.92 |
| Attrition Rate | 16.08% |
| Attrition Count | 238 |

---

## 📌 Dashboard Features

### Employee Summary
- Total Employees
- Average Salary
- Average Age
- Attrition Rate
- Attrition Count

### Attrition Analysis
- Attrition Count by Department
- Attrition Count by Gender
- Attrition Count by Job Role
- Attrition Count by Age Group

### Interactive Filters
- Department
- Business Travel
- Age Group
- Gender

---

## 🔍 Key Insights

### Department-wise Attrition
- Research & Development department has the highest attrition.
- Sales department experiences the second-highest attrition.
- Human Resources department shows the lowest attrition.

### Job Role Analysis
- Laboratory Technicians have the highest attrition count.
- Sales Executives and Research Scientists are among the top job roles affected by attrition.
- Research Directors and Managers have relatively lower attrition rates.

### Age Group Analysis
- Employees aged 26–35 show the highest attrition.
- Employees aged 18–25 also contribute significantly to employee turnover.
- Attrition decreases as employee age increases.
- Employees aged 55+ have the lowest attrition.

### Gender Analysis
- Male employees show higher attrition compared to female employees.

---

## 🛠 Data Cleaning & Transformation

The following transformations were performed using Power Query:

- Removed duplicate records.
- Handled missing values.
- Verified and corrected data types.
- Created age group categories.
- Cleaned and standardized data fields.
- Prepared data for analysis and visualization.

---

## 📐 DAX Measures Used

### Total Employees

```DAX
Total Employees =
COUNT(Employee[EmployeeID])
```

### Attrition Count

```DAX
Attrition Count =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)
```

### Attrition Rate

```DAX
Attrition Rate % =
DIVIDE([Attrition Count], [Total Employees], 0) * 100
```

### Average Salary

```DAX
Average Salary =
AVERAGE(Employee[MonthlyIncome])
```

### Average Age

```DAX
Average Age =
AVERAGE(Employee[Age])
```

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Visualization
- Data Cleaning
- Data Modeling

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Analysis
- DAX Calculations
- Data Modeling
- Dashboard Design
- Business Intelligence
- HR Analytics
- Data Visualization
- Insight Generation

---

## 📊 Business Impact

This dashboard helps HR professionals:

- Monitor employee turnover trends.
- Identify high-risk employee groups.
- Understand workforce demographics.
- Improve retention planning.
- Support strategic HR decision-making.

---

## 🔮 Future Enhancements

- Attrition Prediction using Machine Learning.
- Employee Performance Analysis.
- Department-wise Salary Analysis.
- Employee Satisfaction Analysis.
- Workforce Diversity Metrics.

---

## 👨‍💻 Author

**Udaykumar-analyst**

GitHub: https://github.com/udaykumar-analyst

LinkedIn: http://www.linkedin.com/in/udaykumar-kamble-0241363b4

Email: udaykumarwork555@gmail.com
