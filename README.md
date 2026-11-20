# Employee Attrition and Performance Analysis

An interactive HR Analytics dashboard built using **Microsoft Power BI** to analyze employee attrition, workforce demographics, job satisfaction, employee performance, and retention patterns.

## Project Overview

This project focuses on analyzing HR data to identify patterns and factors associated with employee attrition and workforce performance.

The dashboard provides interactive visualizations and department-level employee insights to support data-driven HR analysis.

**Important:** This project uses the IBM HR Analytics sample dataset obtained from Kaggle. It does not contain actual TCS employee records.

## Project Objectives

- Analyze employee attrition patterns.
- Understand workforce demographics.
- Evaluate job satisfaction and performance.
- Examine the relationship between overtime and attrition.
- Analyze department-wise employee distribution.
- Identify workforce trends through interactive dashboards.

## Dataset Information

| Attribute | Details |
|---|---|
| Dataset | IBM HR Analytics Employee Attrition & Performance |
| Source | Kaggle |
| Records | 1,470 |
| Columns | 35 |
| Format | CSV |
| Data type | Sample HR analytics data |

The dataset includes employee age, gender, department, job role, monthly income, overtime, job satisfaction, performance rating, years at company, and attrition status.

## Tools and Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Kaggle Dataset

## Dashboard Pages

### 1. HR Overview
- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate
- Average Monthly Income
- Attrition by Department
- Attrition by Gender
- Attrition by Overtime
- Attrition by Age Group

### 2. Demographics & Attrition
- Employee Distribution by Age Group
- Employee Distribution by Department
- Employee Distribution by Gender
- Attrition Rate by Marital Status
- Attrition Rate by Education Field
- Attrition Rate by Job Role

### 3. Performance & Retention
- Average Job Satisfaction
- Average Performance Rating
- Average Job Involvement
- Overtime Percentage
- Attrition Rate by Job Satisfaction
- Attrition Rate by Job Involvement
- Attrition Rate by Years at Company
- Monthly Income vs Performance Rating

### 4. Employee Details & Workforce Insights
- Department-wise employee records
- Employee-level information
- Monthly income and tenure details
- Job satisfaction and performance information
- Department-based drill-through functionality

## Key Dataset Observations

- Total employees: 1,470
- Employees with attrition: 237
- Active employees: 1,233
- Overall attrition rate: 16.12%
- Average monthly income: ₹6,502.93
- Average employee age: 36.92 years

These figures describe the sample dataset, not TCS's workforce.

## Interactive Features

- Department, Gender, Overtime and Age Group slicers
- Synchronized slicers across main dashboard pages
- Interactive chart filtering
- Department-wise drill-through
- Employee-level detail table
- Navigation between dashboard pages
- Drill-through back navigation

## Testing Results

The dashboard was manually tested using 20 test cases.

| Testing Metric | Result |
|---|---:|
| Total Test Cases | 20 |
| Passed | 20 |
| Failed | 0 |
| Defects Reported | 0 |

Testing covered navigation, slicers, KPI calculations, chart interactions, department drill-through, employee records, and save/reopen functionality.

## Project Structure

```text
Employee-Attrition-Performance-Analysis/
│
├── README.md
├── Dashboard/
│   └── TCS_Employee_Attrition_Performance_Analysis.pbix
│
├── Dataset/
│   └── Employee_Attrition_Dataset.csv
│
├── Documentation/
│   ├── Project_Report.pdf
│   └── Unit_Test_Results.xlsx
│
└── Screenshots/
    ├── HR_Overview.png
    ├── Demographics_Attrition.png
    ├── Performance_Retention.png
    └── Employee_Details.png
```

*The structure above represents the planned repository organization. Files will be added as they are prepared.*

## How to Use

1. Download the Power BI `.pbix` file from this repository once available.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` file.
4. If Power BI requests the source CSV location, update the data source path.
5. Refresh the data if required.
6. Explore the dashboard using its slicers, charts, and drill-through features.

## Project Deliverables

- Power BI Dashboard
- Project Design Document
- Unit Test Results and Defect Log
- Dashboard Screenshots
- Application Execution Video
- Project Summary PDF

## Author

**Sachin Singh**

B.Sc. Information Technology Student

GitHub: https://github.com/Sachin-tool

---

*This project was developed for academic and learning purposes as part of an Employee Attrition and Performance Analysis industry project.*
