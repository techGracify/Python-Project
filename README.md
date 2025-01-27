# Employee Performance Ratings and Salary

## Project Overview

Employee performance is a key determinant of organizational success. Having the knowledge of what drives performance can help managers improve productivity and create better work environments.     
This dataset includes attributes such as age, salary, years of experience and department etc, with the mindset of exploring how these factors influence employee performance ratings.
The analysis will uncover insights that could guide human resources strategies from recruitment to performance management.


![pyscrn](https://github.com/user-attachments/assets/03570966-8911-41b9-aa3d-0c43ba104fec)

## Data Source
The dataset was gotten from kaggle website, it consists 1,000 rows and 12 columns, each representing an employee’s details and its features are as follows:
- 	ID:		Unique identifier for each employee.
- 	Name:	Names of the employees.
-  Age:		Employee’s age.
- Gender:	Gender of the employee
-	Department:	The department where the employee works.
-	Salary:	Monthly salary of the employee.
-	Joining Date:	Date when the employee joined the company.
-	Performance Rating: Rating of employee’s performance (originally called employee Score)
-	Status: Current status of the employee (active/inactive)
-	Location:	Location where the employee is based.
-	Session:	The work session or shift assigned to the employee.

## Tools
Python - Data Cleaning, Data Manipulation, Data Analyis and Data Visualization.
## Data Cleaning and Preparation.
The following methods were carried out in the preparation of our data:
- Handling Missing Values
- Checking for duplicate rows.
- Confirming Data Type
- Renaming of columns.
## Data Analysis
This project was carried out in Python and numereous pandas functions were used to derive actionable and meaningful insights.
## Result/Findings
The Analysis results/findings are summarised as follows:
### Correlation between salary and Performance Rating:
Higher salaries may be linked to better performance ratings and years of  experience in certain departments.
### Experience and Performance: 
Employees with more years of experience tend to have higher performance ratings, but this correlation may vary by department.
### Gender Distribution: 
There may be imbalances in gender representation across departments, which could impact overall performance assessments.
### Department-wise Analysis: 
Certain departments (e.g., IT, HR) might show higher performance ratings due to the nature of work and expectations.
## Recommendation
- Targeted Training Programs: For departments with lower performance ratings, consider introducing tailored training programs to address skill gaps.

-	Salary Revisions: Employees with higher experience but lower performance ratings may benefit from salary adjustments or motivational incentives.

-	Diversity and Inclusion Initiatives: Promote a balanced gender representation in departments where performance is tilted by gender imbalances.

-	Performance Monitoring: Continue regular monitoring of performance ratings to identify early signs of underperformance, especially in departments with high turnover rates.

## Limitations
I had to change all the zeros in the Years of Experience column from float (decimal numbers) to integers (whole numbers) because the extra values were mostly zeros for a clearer analysis.
