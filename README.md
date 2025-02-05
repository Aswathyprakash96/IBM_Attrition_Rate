**IBM Employee Attrition Dataset**
This dataset contains information about employees at IBM, and the goal is to predict employee attrition (whether an employee leaves the company or not).
It includes various features such as employee demographics, work-related details, and other factors that may influence employee attrition.
**# Column Explanations**
The dataset can be used to build machine learning models to predict employee churn, understand the underlying factors contributing to attrition, and develop strategies to retain employees.
1.Age: The age of the employee. This is a continuous numerical feature. Age can be a factor in attrition as it could correlate with job satisfaction and career stage.
2.Attrition: The target variable, indicating whether the employee left the company (Yes) or stayed (No). This is a categorical feature, where 'Yes' represents an employee who left (attrition) and 'No' represents an employee who stayed.
3.BusinessTravel: The frequency with which the employee travels for work. It can have three possible values:
    1. Travel_Rarely
    2.Trvael_Frequently
    3.Non_Traveller
4.DailyRate: The daily rate of pay for the employee. This is a numerical feature and could be related to job satisfaction and retention.
5.Department: The department in which the employee works.certain departments can have higher or lower attrition rates.
6.DistanceFromHome: The distance (in miles) between the employee's home and the company. Employees with a long commute might experience higher job dissatisfaction, leading to higher attrition.
7.Education: The level of education the employee has completed.Education might correlate with career opportunities and job satisfaction.
8.EducationField: The field in which the employee obtained their education.
9.EmployeeCount: This is usually a constant value (e.g., 1) representing the count of employees. It's likely not a very useful feature for modeling.
10.EmployeeNumber: A unique identifier assigned to each employee. This is generally used for referencing the employee and doesn't provide meaningful information for prediction tasks.
11.EnvironmentSatisfaction: The employee's satisfaction with their work environment, on a scale from 1 to 4, where 1 is very dissatisfied and 4 is very satisfied. Higher satisfaction likely correlates with lower attrition.
12.Gender: The gender of the employee. It's a categorical feature with possible values such as Male and Female. Gender may have an indirect effect on attrition if there are any biases or systemic differences in how employees are treated.
13.HourlyRate: The hourly rate the employee earns. A higher hourly rate could be linked to job satisfaction and lower attrition.
14.JobInvolvement: The employee's level of involvement in their job, scored on a scale from 1 to 4, where 1 is low involvement and 4 is high involvement. More engaged employees may have lower attrition.
15.JobLevel: The job level the employee holds within the company, often ranging from 1 (entry-level) to 5 (senior-level). Job level can affect attrition, as employees in higher levels may be more likely to stay due to promotions and career growth opportunities.
16.JobRole: The role the employee holds within the company.Different roles might have varying attrition rates due to job demands and growth opportunities.
17.JobSatisfaction: The employee’s satisfaction with their job on a scale from 1 (very dissatisfied) to 4 (very satisfied). High job satisfaction is generally associated with lower attrition.
18.MaritalStatus: The marital status of the employee,might indirectly influence an employee’s work-life balance and, therefore, their likelihood of staying with the company.
19.MonthlyIncome: The monthly income of the employee. Higher income could be associated with lower attrition, as employees may be more likely to stay in their current job if the pay is competitive.
20.NumCompaniesWorked: The number of companies the employee has worked for in the past. A higher number of previous companies could indicate less loyalty or dissatisfaction with past employers, potentially leading to higher attrition.
21.OverTime: Whether the employee works overtime or not. It is a binary categorical feature (e.g., Yes or No). Working overtime might cause burnout or dissatisfaction, potentially leading to attrition.
22.PercentSalaryHike: The percentage increase in the employee's salary during the last year. Higher salary increases may correlate with higher employee satisfaction and lower attrition.
23.PerformanceRating: The employee’s performance rating, typically on a scale from 1 to 4. A higher performance rating could be associated with better career growth opportunities and lower attrition.
24.RelationshipSatisfaction: The employee's satisfaction with relationships with colleagues and supervisors, on a scale from 1 (very dissatisfied) to 4 (very satisfied). Strong relationships are often linked with lower attrition.
25.StandardHours: The standard number of hours an employee is expected to work. This is often constant and might not be a very useful feature.
26.StockOptionLevel: The level of stock options provided to the employee, typically 0, 1, or 2. Stock options could be a significant retention tool for employees.
27.TotalWorkingYears: The total number of years the employee has worked in their career. This might influence their likelihood of staying or leaving, as more experienced employees may have different retention patterns.
28.TrainingTimesLastYear: The number of training sessions the employee participated in during the past year. Higher training could indicate greater investment in the employee's growth, which may lead to lower attrition.
29.WorkLifeBalance: The employee's perception of their work-life balance, on a scale from 1 (bad) to 4 (good). A good work-life balance is often linked to higher job satisfaction and lower attrition.
30.YearsAtCompany: The number of years the employee has worked at the company. Long-tenured employees may be less likely to leave due to higher loyalty or seniority.
31.YearsInCurrentRole: The number of years the employee has spent in their current role. Employees in the same role for many years might experience boredom or stagnation, potentially increasing attrition.
32.YearsSinceLastPromotion: The number of years since the employee was last promoted. Employees who haven't been promoted in a long time may feel undervalued and are more likely to leave.
33.YearsWithCurrManager: The number of years the employee has worked with their current manager. Strong relationships with managers may lead to lower attrition.
**Objective**
The primary objective is to predict employee attrition (whether the employee will leave or stay) based on various features such as job satisfaction, salary, work-life balance, and other employee demographics.
**Data Preprocessing**
Before building models, the following preprocessing steps were taken:
Data Cleaning:
Missing values were handled (either imputation or removal).
Categorical variables were encoded using techniques like One-Hot Encoding or Label Encoding.
Features were normalized using techniques like Standard Scaler.
Splitting Data:
The data was split into training and testing sets for model evaluation.
Feature Selection:
Important features were identified, and less relevant features were removed for better model performance.
**Models Used**
Several machine learning models were tested on this dataset, including:
Logistic Regression:
A linear model for binary classification to predict employee attrition.
Achieved an accuracy of 76.32%.
Random Forest Classifier:
An ensemble method that builds multiple decision trees to make predictions.
Achieved an accuracy of 96.36%, showing its superior performance over Logistic Regression.
**CONCLUSION**
Random Forest Classifier outperformed Logistic Regression by a significant margin, achieving an accuracy of 96.36% compared to Logistic Regression’s 76.32%.
