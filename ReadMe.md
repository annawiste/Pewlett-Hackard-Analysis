
# Pewlett-Hackard Retirement Eligbility

## Overview
Pewlett-Hackard is faces an upcoming challenge due to its aging workforce. The company will need a strategic plan for the upcoming transition as large numbers of senior, experienced employees will likely leave in a short period of time. The current analysis begins to assess the scope of the issue, identifying these employees and which positions within the company are going to be most affected. 
Next, employee information is provided for individuals who may be candidates for a proposed mentorship program, working with retiring employees to prepare for taking on those positions. 

## Results
- The most recent titles for employees who are soon retirement eligible age are most likely to be Senior Engineer and Senior Staff.

![table](retiring_employees.png)

- Two managers are in this age bracket. These roles will likely be the most important to fill, but will also require an inividualized approach to identifying potential replacements. 

- There were 1549 individuals identified as eligible for the proposed mentorship program.

- The total number of individuals included in the table for retirement by title is 133776. This number does not make sense given our earlier analysis identified only 33,118 current employees at retirement age. 

## Summary
The table included here, with the number of individuals with each title, includes all individuals who have been employees, and are now approaching retirement eligible age. However, it was not constrained on current status of employment, and thus includes individuals who no longer work for the company. I went back to the queries and added the constraint of current employment. Almost 18000 individuals were filtered out, leaving a new table. 

![newtable](retiring_current_employees.png)

While there are fewer employees at every title other than manager, the change is larger proportionally for those in more junior positions. There remain 50,000 individuals in senior roles who will be retiring, but there is less cause for concern regarding retirement in more junior roles. 

The analysis identified 1549 individuals who would be eligible for the mentorship program. These individuals are all current employees of the company. However, they are chosen by date of birth, 1965. The youngest employees in the dataset have a birthdate of 2/1/65, so the parameter used to define potential mentees, includes only individuals born in one month. Its not clear that date of birth is the best option for filtering here anyway, and certainly not including only one month. An alternative approach that may be helpful would be to look for current employees at the staff level, as potential replacements for senior staff. And also look for current engineers as potential replacements for senior engineers. These queries would capture a broader group of possible mentees, while also yielding groups more specifically targeted to the areas of need.  

