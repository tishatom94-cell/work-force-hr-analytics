# work-force-hr-analytics
The HR Analytics dashboard provides actionable insights into workforce demographics, compensation, absenteeism, and productivity. Findings highlight areas of concern such as absenteeism, salary equity, and overtime dependency. 

**CREATE CALCULATED COLUMNS**
Total Leaves = Sick Leaves + Unpaid Leaves.
Overtime Pay = Overtime Hours * Job Rate.

**CREATE KPIS**
Headcount = COUNTROWS(Workforce)
Average Salary = AVERAGE(Workforce[Annual Salary])
Attrition Rate (if you add attrition flag later) = DIVIDE(AttritionCount, Headcount)
Average Sick Leaves = AVERAGE(Workforce[Sick Leaves])
Overtime Hours per Employee =AVERAGE( Workforce [Overtime Hours]

**DASHBOARD**
Gender distribution (pie chart).
Department-wise headcount (bar chart).
Country/Center breakdown (map or stacked bar).
Salary distribution by department.
Monthly vs Annual salary comparison.
Overtime pay contribution.
Sick vs Unpaid leaves by department.
Trend of leaves across tenure groups.
Overtime hours by department.
Correlation between job rate and overtime.

**The Workforce HR Analytics Dashboard provides a holistic view of employee demographics, compensation, absenteeism, and productivity.
It highlights diversity gaps, compensation inequities, and workload imbalances.
It empowers HR leaders to design targeted interventions: diversity initiatives, fair pay structures, wellness programs, and workload redistribution.
Ultimately, the dashboard supports data-driven workforce management, improving engagement, reducing costs, and driving sustainable productivity**
