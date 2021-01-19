# Pewlett-Hackard-Analysis

## Overview of the analysis:

The purpose of this analysis was to find out how many employees were retiring from Pewlett-Hackard, and to then 
ask those retiring if they were willing to keep working part time as mentors to the younger employees. I used SQL instead of Pewlett-Hackard's
older tools (EXCEL and VBA) in order to streamline the process. ***I retrieved those who were born from 1952 to 1955 to check for retirement.***

## Results

Using SQL and PostgreSQL on PG Admin4, I managed to retrieve all of the employees from each department of the company
that were retiring. Here is what I found out:

1) The highest number of those retiring or close to retiring were **Senior Engineers** or **Senior Staff**. Third highest count of retirees had the 
**Engineer** job title.

This image shows the number of people eligible for retirement for each department:

![retired_emp_count](https://github.com/Kyle2Miles93/Pewlett-Hackard-Analysis/blob/main/retired_emp_count_screenshot.png)

2) Department 5 (d005), or the Development department, turns out to have the highest number of employees: 9,281 total.

3) Through querying for data with SQL, I discovered that there were many duplicate entries in the employee csv file that I recieved.
The data is also unclean in various other ways. For example, the employees whose "to_dates" were in the year 1999 were labeled as '9999'
invariably. Also, it is interesting to note that there are a lot of poeple with Japanese or Chinese first names and European 
(perhaps Northern European or Slavik) last names. <- This has not much to do with the analysis, but I thought it was interesting.

4) There were only **2** managers retiring. 

## Summary

Hewlett-Packard could benefit from first cleaning their data using SQL queries in PostgreSQL. We could create new tables and export the resulting csv files after
this is done. 

With regards to the results, the company should definitely focus their resources on training the retiring senior engineers or senior staff employees
on their mentorship programs. If any of them are on the fence about continuing to work part-time, perhaps they could be incentivized. Since there are only two managers retiring or close to retiring, perhaps it wouldn't hurt if they were allowed to develop their own mentorship strategy on their own. The point being:
those whose postition contains the most retirees, focus of hiring in those departments and roles, and also focus
on creating a mentorship program which systematically trains the retiring employees to mentor.
