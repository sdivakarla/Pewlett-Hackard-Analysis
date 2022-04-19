# Pewlett Hackard Analysis

# Overview

The company Pewlett Hackard is concerned about the number of employees that will be retiring in the upcoming years. The company requested a review of the current status of employees as well as future predictions. 

# Results

The employee data from Pewlett Hackard was analyzed using Structured Querly Language (SQL) in the program PGAdmin.  The first deliverable was a table of the number of retiring employees, sorted by titles. Multiple employees had more than one title, so it was necessary to find their current title.  If they had been with the company a while, it is possible they had a promotion or had moved positions and, there fore had multiple title. Results are summarized below: 
- The unique_titles.csv contains the current title of the employees of retirement age.  Theere are 72,458 employees currently eligible to retire.  Retirement age was determined to be those employees born between January 1, 1952 and December 31, 1955. 
- The vast majority of those employees eligible to retire are "Senior" level staff (50,842/72,548, or 70%), as can be seen in the table below.

![retiring_table](https://user-images.githubusercontent.com/98054953/164112161-3292ff4b-517d-49d0-a006-3c428d0eedc5.png)

A second analysis was performed to determine which employees were eligible for a mentorship program to address this large number of retiring employees. 
The results are summarized below: 

- 1,549 employees were identified as potential participation in the mentorship program.  The majority of these employees are currently listed as "Staff". 
- The employees eligible for the mentorship program were identified as those employees born between January 1, 1965 and December 31, 1965. 

The mentorship eligible employees are summarized below: 

![potential_mentor](https://user-images.githubusercontent.com/98054953/164112584-84d1439d-7423-4bc9-ba4f-efcd41b22ab3.png)

# Summary 

Pewlett Hackard has a large number of employees ready to retire.  The identified employees for the mentorship program only represent 2% of the retiring employees.  Pewlett Hackard may need to loosen the restrictions on the mentoring program or actively work to hire employees to train in light of the upcoming retirements. 
