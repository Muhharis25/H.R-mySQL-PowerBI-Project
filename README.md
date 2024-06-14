# H.R-mySQL-PowerBI-Project

<img width="1446" alt="Screenshot 2024-06-14 at 5 40 05 PM" src="https://github.com/Muhharis25/H.R-mySQL-PowerBI-Project/assets/168931332/871a0092-e735-4877-9583-59d1b8250a4b">

# Data Used
Data - HR Data with over 22000 rows from the year 2000 to 2020.

Data Cleaning & Analysis - MySQL Workbench

Data Visualization - PowerBI

#Question

What is the gender breakdown of employees in the company?
What is the race/ethnicity breakdown of employees in the company?
What is the age distribution of employees in the company?
How many employees work at headquarters versus remote locations?
What is the average length of employment for employees who have been terminated?
How does the gender distribution vary across departments and job titles?
What is the distribution of job titles across the company?
Which department has the highest turnover rate?
What is the distribution of employees across locations by state?
How has the company's employee count changed over time based on hire and term dates?
What is the tenure distribution for each department?

#Findings

There are more male employees
White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
The youngest employee is 20 years old and the oldest is 57 years old
5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
A large number of employees work at the headquarters versus remotely.
The average length of employment for terminated employees is around 7 years.
The gender distribution across departments is fairly balanced but there are generally more male than female employees.
The Marketing department has the highest turnover rate followed by Training. The least turn over rate are in the Research and development, Support and Legal departments.
A large number of employees come from the state of Ohio.
The net change in employees has increased over the years.
The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.

#Limitations
During the data analysis, 967 records with negative ages were excluded, and a 'dob_flag' column was added to indicate these invalid dates of birth. Only records with ages 18 years and above were used. 
Additionally, 1,599 records with termination dates far into the future were excluded. Only termination dates less than or equal to the current date were included in the analysis.
