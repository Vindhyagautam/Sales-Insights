#Objective:
In this exercise, you will use Power BI to analyze box office data for a set of movies, create engaging visuals, and extract meaningful insights.

#Task:
1.Import the data and open the Power Query.

2.The expense type column has some spelling and punctuation errors, correct them.
3.Project names are not uniform, make it uniform.

4.The Currency column has some missing values, based on the amount, create a new custom column.
5.Formula: (if [Currency] = null and [Amount] >= 1000 then "INR" else if [Currency] = null and [Amount] < 1000 then "USD" 
  else [Currency] )

6.Normalize the amount column into INR based on the currency column.   

7.Create a measure to calculate the sum of reimbursed amount in INR.

8.Use the calculate function and check the total reimbursed amount for Project_B.

9.Create a measure to check the count of declined requests.

10.Create a slicer visual for the Project and employee.

11.Create a bar chart for employees and reimbursement amount.

12.Create a pie chart for Project vs reimbursement amount

DashBoard for the performed Task:

![Screenshot 2024-04-02 201034](https://github.com/Vindhyagautam/Sales-Insights/assets/164732296/e1522e6e-8acb-4eff-ae1b-fde0de8a385a)
 
