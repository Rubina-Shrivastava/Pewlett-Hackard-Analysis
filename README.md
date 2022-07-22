# Pewlett-Hackard-Analysis
 ## Overview of Project:
   ### The purpose of this analysis is to prepare Pewlett-Hackard, a large company, for the upcoming “Silver Tsunami”, for this we determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program and current employees reach retirement age.  The criterion was based on the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.
 ##  Resources :
  ### Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
  ### Software: SQL, PostgreSQL, pgAdmin 
 ##  Results :
  ### ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee plan to facilitate the analysis. 
  ### Entity Relationship Diagram 
![Entity Relationhip Diagram](https://github.com/Rubina-Shrivastava/Pewlett-Hackard-Analysis/blob/main/EmployeeDB(ERD).png)
 ### Mentorship Candidates: List of candidates, that can qualify to become members of the mentorship program, they can be referenced as "Senior" employees amongst the general staff.
 ### Mentorship Eligiblity CSV
![Mentorship Eligibility](https://github.com/Rubina-Shrivastava/Pewlett-Hackard-Analysis/blob/main/mentorship_eligibilty.png)
 ### Future Job Openings:
### After conducting the analysis it was found that there is currently a large number of employees of retirement age holding senior titles. Please reference the table below.
 ### Retiring Titles
![Retiring Titles](https://github.com/Rubina-Shrivastava/Pewlett-Hackard-Analysis/blob/main/retiring_titles.png)
 ## Summary:
 ### As the "Silver Tsunami" begins to make an impact, there are 90,398 roles that will need to be filled across 7 different categories in the organization.  At the moment at Hackard Pewlett, 64% of their employees are getting ready for retirement or being redirected to their mentorship initiatives, which will mean that they are likely going to need an extensive hiring process in the upcoming years. Since a significant amount of future retirees hold Senior positions, the mentorship program should provide a capacitation buffer for the extensive expertise that will be leaving the company in the years to come.
 ### With 1,549 employees available for the mentorship program, it seems that there are not enough qualified employees ready for retirement in the departments to mentor the next generation of employees. Each mentor would have to have about 58 mentees, which is much too large of a workload for any employee, especially part-time retiring employees. By breaking down the mentorship eligible employees by department in the query below, we can see that the employees are proportionally spread to the employees that are retiring but there is still too few employees to mentor the retiring employees.
![Mentorship](https://github.com/Rubina-Shrivastava/Pewlett-Hackard-Analysis/blob/main/mantorship.png)
