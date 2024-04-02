Objective:
In this exercise, you will use Power BI to analyze box office data for a set of movies, create engaging visuals, and extract meaningful insights.

Task:
-
Import the data and open the Power Query.
-
The expense type column has some spelling and punctuation errors, correct them.
-
Project names are not uniform, make it uniform.
-
The Currency column has some missing values, based on the amount, create a new custom column.
Formula: (if [Currency] = null and [Amount] >= 1000 then "INR" else if [Currency] = null and [Amount] < 1000 then "USD" else [Currency] )
-
Normalize the amount column into INR based on the currency column.   
-
Create a measure to calculate the sum of reimbursed amount in INR.
-
Use the calculate function and check the total reimbursed amount for Project_B.
-
Create a measure to check the count of declined requests.
-
Create a slicer visual for the Project and employee.
-
Create a bar chart for employees and reimbursement amount.
-
Create a pie chart for Project vs reimbursement amount

DashBoard for the performed Task:

https://github.com/Vindhyagautam/Sales-Insights/issues/2#issue-2220735322
 
