# HR-Analytics

Dataset is obtained from the Kaggle Website.
https://www.kaggle.com/giripujar/hr-analytics#HR_comma_sep.csv

## Objective
1. Understand what factors contribute most to employee turnover. 
2. Create a model that can predict if a certain employee will leave the company or not.

# Interpretation of the data
Employee satisfaction, yearsAtCompany, and evaluation were the three biggest factors in determining turnover.

1. Employees with low to medium salaries are more likely to leave the company. It is observed that the employees with high salaries are least likely to leave the company.
2. The employee turnover is high in the departments Sales, techincal, Support. The Management departmnet has the least employee turnover.
3. The employee turonver is high for employees with 2,6 and 7 projects. Majority of the employees with 3,4,5 projects did not leave the company. All the employees with 7 projects left the company.
4. Employees with low and high performance tend to leave the company more. The sweet spot for employees that stayed is within 0.6-0.8 evaluation.
5. Employees who had less hours of work (150hours or less) left the company more. Employees who had too many hours of work (250 or more) left the company Employees who left generally were underworked or overworked.
6. Employees who had really low satisfaction levels (0.2 or less) left the company more Employees who had low satisfaction levels (0.3~0.5) left the company more Employees who had really high satisfaction levels (0.7 or more) left the company more.
7. More than half of the employees with 4 and 5 years left the company.
8. Looks like employees who did not leave the company had an average evaluation of around 70% even with different projectCounts. There is a huge skew in employees who had a turnover though. It drastically changes after 3 projectCounts. Employees that had two projects and a horrible evaluation left. Employees with more than 3 projects and super high evaluations left.

# Best - Model
Random Forest Model is identified as best model with AUC of 0.98
