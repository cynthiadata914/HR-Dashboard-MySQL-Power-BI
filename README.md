# HR-Dashboard-MySQL-Power-BI

## Data Used

Data - HR Data with over 22000 rows from the year 2000 to 2020.

Data Cleaning & Analysis - MySQL Workbench.

Data Visualization - PowerBI.

## Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average lenght of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by states?
10. How has the comapany's employee count chsnged over time based on the hire and term date?
11. What is the tenure distribution for each department? 

## Summary of Results

- There are more male employees
- White race is the most dominant while Native Hawaiin and American Indian are the least dominant.
- The youngest employee is 20 years old and the oldest is 57 years old
- 5 age groups were created (18-24,25-34,35-44,45-54,55-64).A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
- A large number of employees work at the headquarters versus remotely.
- The average lenght of employment for terminated employees is around 7years.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.
- The Marketing department has the highest turnover rate followed by Training. The least turnover rate are in the Research and development,Support and Legal departments.
- A large number of employees come from Ohio.
- The net change in employees has increased over the years.
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services,Sales and Marketing having the lowest.

## Limitations

-Some records had negative ages and theses were excluded during querying(967 records).Ages used were 18 years and above.
Some termdates were far into the future and were not included in the analysis(1599 records).The only term dates used were those less than or equal to the current date.
