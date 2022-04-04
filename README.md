# Pewlett-Hackard-Analysis

#PURPOSE

	Bobby's manager has been pleased with our work so far and has given us another project. The purpose of our project is to analyze the number of retiring employees by title and pinpoint which employees are eligible to to participate in the mentorship program. Our retiring titles table information will show the titles of all employees born between January, 1 1952 and December, 31 1955. First, Boby and I created a query that retrieved the emp_no, first_name and last_name columns from the employees table and retrieved the title, from_date and to_date columns of the titles table in our Pewlett-Hackard query. We joined both of these table on the primary key, filtered the data by birth_date, and put the data into a new table. Next, we created a unique_titles table to find the first showing of the emp_no in our new table by using the DISTINCT ON function and we did ORDER BY COUNT to show us the total number of each title from our unique_titles table that we created earlier. The 2nd deliverable we created a query that retrieved columns from our employees and dept_emp table, filtered data on current employees born in 1965 then ordered the table by emp_no. This query created our table to show the employees eligible for the mentorship program.

![alt text](C:\Users\lawre\OneDrive\Documents\GitHub\Pewlett-Hackard-Analysis\retirees_titles.png)

![alt text](C:\Users\lawre\OneDrive\Documents\GitHub\Pewlett-Hackard-Analysis\retiring_titles.png)


#RESULTS


	With the retirment_titles table we are able to see every eligible for retirement employee and how long they have worked at each position over the course of their tenure.

	The unique titles table that we created is showing the most recent title for employees of retirment age.	

	Our retiring_titles shows us the a majority of the employees of retirment age. The number of employees of retirement age compared to the number of employees equals 57,668/90,398, which is 64%. 

![alt text](C:\Users\lawre\OneDrive\Documents\GitHub\Pewlett-Hackard-Analysis\unique_titles.png)

	The final part of our project shows mentorship eligibility, if you look at the head of the new csv - you can see that most of these employees have senior titles.

![alt text](C:\Users\lawre\OneDrive\Documents\GitHub\Pewlett-Hackard-Analysis\mentorship_eligibility.png)

#CONCLUSION

	At the moment at Pewlett Hackard, 64% of their employees are getting ready for retirement or being redirected to their mentorship initiatives, which will mean that they are likely going to need an extensive hiring process in the upcoming years. This a challenge but also a great opportunity to learn from these individuals on what made them successful and how they stayed motivated to have such long lasting careers. This can have a huge impact on the next hiring classes to come. The mentorship program would be vital so that the future retirees and share there knowledge and the new recruits can take that information and raise the bar higher on what Pewlett-Hackard could accomplish. 

