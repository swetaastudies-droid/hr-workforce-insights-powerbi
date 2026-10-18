# HR Workforce Insights & Employee Attrition Predictor Dashboard

An interactive Power BI project that explores workforce composition, employee attrition, satisfaction, overtime, and retention opportunities through data visualization and business analysis.

## Project Objective

The objective of this project is to transform employee data into actionable workforce insights. The dashboard helps users explore attrition patterns across departments, job roles, tenure, and employee experience indicators to support HR analysis and workforce planning.

## Tools Used

- **Microsoft Power BI Desktop** — dashboard development and visualization
- **Power Query** — data cleaning and transformation
- **DAX (Data Analysis Expressions)** — KPI calculations and analytical measures
- **Microsoft Excel / CSV** — dataset storage and preparation
- **GitHub** — project documentation and portfolio publishing

## Dataset Description

The project uses a synthetic employee dataset containing 200 employee records.

Key fields include:

- Employee ID, age, gender, and department
- Job role, education level, marital status, and location
- Joining date and years at company
- Monthly income, performance rating, and training hours
- Overtime status and work mode
- Job satisfaction and work-life balance scores
- Promotion status and absenteeism rate
- Attrition status and illustrative attrition risk level

**Data note:** The dataset is synthetic and is intended for learning and portfolio demonstration. The attrition risk categories are illustrative, rule-based labels, not validated machine-learning predictions.

## Power Query Steps

The following preparation steps were used or are intended for the Power BI workflow:

1. Imported the employee dataset into Power BI Desktop.
2. Reviewed column names and data quality.
3. Assigned appropriate data types to numeric, text, and date fields.
4. Checked missing values and duplicate Employee IDs.
5. Standardized categorical values where necessary.
6. Created derived categories such as age group, tenure band, and salary band.
7. Checked valid ranges for age, income, and employee scores.
8. Applied the transformations and loaded the cleaned data into the Power BI model.

## DAX Measures

The dashboard includes measures for:

- **Total Employees** — distinct employee count.
- **Current Employees** — records marked as not attrited.
- **Attrition Count** — records marked as attrited.
- **Attrition Rate %** — attrited records divided by total records.
- **Average Monthly Income** — average monthly income.
- **Average Job Satisfaction Score** — average satisfaction score.
- **Average Work-Life Balance Score** — average work-life balance score.
- **Average Training Hours** — average training hours.
- **High Attrition Risk Employees Count** — records in the illustrative High category.
- **Medium-Risk Employees** — records in the illustrative Medium category.
- **Low-Risk Employees** — records in the illustrative Low category.
- **Current High Risk Employees** — records marked as current employees and assigned the illustrative High category.

The attrition percentage represents the proportion of records marked as attrited in this dataset. It is not an annual attrition rate because exit dates and a defined reporting period are not available.

## Dashboard Features

The report is organized into four pages:

### 1. Executive Overview
- Workforce KPI cards
- Total and current employee records
- Attrition count and sample attrition proportion
- Average monthly income and illustrative risk counts

### 2. Attrition Analysis
- Attrition by department
- Attrition by job role
- Attrition status breakdown
- Department-level workforce summary

### 3. Workforce Insights
- Workforce composition
- Employee group comparisons
- Relevant demographic and employment characteristics

### 4. Retention Insights
- Overtime and attrition comparison
- Job satisfaction analysis
- Work-life balance analysis
- Illustrative risk category review

Interactive slicers allow users to explore the report by fields such as department, gender, work mode, job role, and attrition risk level.

## Key Insights

The original synthetic sample dataset provides the following illustrative findings:

- Sales and Finance have the highest attrition counts, with eight attrited records each.
- Sales has a sample attrition proportion of 26.7% (8 of 30 records).
- Employees with zero years at the company have a sample attrition proportion of 66.7% (12 of 18 records).
- Records marked as overtime workers have a sample attrition proportion of 31.1%, compared with 14.4% for non-overtime workers.
- The lowest job satisfaction score group has a sample attrition proportion of 44.0%.
- Financial Analyst and Sales Manager each have four attrited records in the original sample.

These are descriptive findings from synthetic data. Differences may indicate areas for further investigation, but they do not establish causation or predict individual employee behavior.

## Screenshots

Add your report screenshots to the `screenshots/` folder and update the image paths below.

### Executive Overview
![Executive Overview](screenshots/executive-overview.png)

### Attrition Analysis
![Attrition Analysis](screenshots/attrition-analysis.png)

### Workforce Insights
![Workforce Insights](screenshots/workforce-insights.png)

### Retention Insights
![Retention Insights](screenshots/retention-insights.png)

## Repository Structure

```text
hr-workforce-insights-powerbi/
├── README.md
├── dataset/
├── powerbi/
├── screenshots/
├── documentation/
└── exports/
```

## Conclusion

This project demonstrates how Power BI, Power Query, and DAX can be used to prepare employee data, build interactive HR dashboards, and communicate workforce insights. It provides a foundation for exploring attrition patterns and developing evidence-based retention and workforce-planning recommendations.

## Limitations

- The dataset is synthetic and does not represent a real organization.
- The sample attrition proportion is not an annual attrition rate.
- Risk categories are illustrative and are not validated predictive scores.
- Observed associations do not establish causation.
- Results may differ if the dataset is changed during cleaning.

## Author

K B SWETAA
