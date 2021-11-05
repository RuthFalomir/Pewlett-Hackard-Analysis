# Pewlett-Hackard-Analysis

## Overview of the analysis: 

We were hired by Pewlett Hackard to participate in their staff analysis in order to come up with a strategic plan to deal with future employees' retirements. We worked with two different projects: the first was to understand how ma ny employees meet certain criteria to be considered in the retirement plants. Second, to understand which positions will need to be filled in the near future once the other group of employees retire. 

Bottom line, we were brought to the team to find out 1) Who will be retiring in the next few years and 2) How many positions will need to be filled?

## Results: 

During our analysis, we used the provided csv files to create new tables with data that was relevant to the questions at hand. We started out with information distributed in 6 different files. We created a DataBase diagram to understand the situation better. 

![EmployeeDB](https://user-images.githubusercontent.com/88563922/140441005-15a3941e-a17c-49ec-9e4d-30b9f2cbf905.png)


* We created a table were we filtered out of total amount of employees, only those who were born between January 1, 1952 and December 31, 1955. This means that they are in the adecuate range to be considered for the retirement package. We can see this data in retirement_titles.csv

* However, this last csv file had several employees who appeared multiple times, since they have worked under different titles throughout the years. In the file unique_titles.csv we can see that there are 90,398 employees who meet the requirement package criteria.

* A new file was created to categorize positions to understand which roles would have the largest amount of retiring employees. The categories and total employees per title can be seen below. 

<img width="140" alt="retirement_titles" src="https://user-images.githubusercontent.com/88563922/140440990-9fbe4603-de36-4395-bdf5-6e374aa58760.PNG">

* Further analysis was done to define which employees would fit into a new mentorship program. 1,549 employees were eligible to participate in said program. We can see the names in the mentorship_elegibility.csv file.



## Summary: 

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?

According to our analysis, Pewlett Hackard will have to fill 90,398 roles. The categories with the most retiring employees are Senior Engineers and Senio Staff. This means that high ranking positions will need to be filled by qualified and prepared younger employees. This will have a huge impact on the company's performance in general and they will have to put special attention to their mentorship program in order to achieve a smooth transition.  

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Only 1,549 employees are eligible for the mentorship program. Compared to the 90,398 employees leaving the company, that's a mere 1.7%. We would recommend that PH widens the eligibility criteria for the mentorship program to increase the amount of mentors available to train young employees. 

Two additional queries we could make are how many younger employees per role/title there are and how many retiring, to get a better sense of how many will leave vs. how many need mentoring. 
Another interesting table would be the younger employees who are about to take the retiring employees positions. 
