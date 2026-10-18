# Project checklist

## Step 1 — Project introduction
- [ ] Confirm project title and objective.

## Step 2 — Dataset
- [ ] Open `01_Dataset/HR_Workforce_Insights_Sample_Dataset.xlsx`.
- [ ] Confirm `Employee_Data` and `Data_Dictionary` sheets.

## Step 3 — Import into Power BI
- [ ] Home > Get data > Excel workbook.
- [ ] Select `Employee_Data` > Transform Data.
- [ ] Rename the query to `Employees`.

## Step 4 — Power Query
- [ ] Set data types.
- [ ] Check missing values and duplicate Employee IDs.
- [ ] Create Age Group, Tenure Band, and Salary Band.
- [ ] Close & Apply.

## Step 5 — DAX measures
- [ ] Total Employees.
- [ ] Current Employees.
- [ ] Attrition Count.
- [ ] Attrition Rate % (label as sample attrition proportion unless a reporting period is defined).
- [ ] Average Monthly Income.
- [ ] Average Job Satisfaction Score.
- [ ] Average Work-Life Balance Score.
- [ ] High/Medium/Low illustrative risk counts.

## Step 6 — KPI cards
- [ ] Total Employees.
- [ ] Current Employees.
- [ ] Attrition Count.
- [ ] Attrition Rate %.
- [ ] Average Monthly Income.
- [ ] High-Risk Employees (illustrative category).

## Step 7 — Report visuals
- [ ] Department attrition chart.
- [ ] Job-role attrition chart.
- [ ] Attrition status chart.
- [ ] Overtime / work-life balance / satisfaction analysis.
- [ ] Workforce summary matrix.
- [ ] Slicers for Department, Gender, Work Mode, Job Role, and Risk Level.

## Step 8 — Professional design
- [ ] Corporate blue theme; green for positive indicators; amber/red for risk-related visuals.
- [ ] Consistent fonts, spacing, alignment, and chart sizing.
- [ ] Add clear page titles and labels.

## Step 9 — Business insights
- [ ] Identify departments with high attrition counts and proportions.
- [ ] Compare employee groups without claiming causation.
- [ ] Investigate overtime, satisfaction, and work-life balance patterns.
- [ ] Identify roles requiring retention review.
- [ ] Recommend evidence-based HR actions.

## Final quality checks
- [ ] Validate all measures and filters.
- [ ] Ensure chart labels and titles are readable.
- [ ] State that data is synthetic and risk labels are illustrative.
- [ ] Save the `.pbix` report and screenshots.
