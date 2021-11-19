# Final Project: Advanced SQL Techniques

### Question 1
Write and execute a SQL query to list the school names, community names and average attendance for communities with a hardship index of 98.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q1.png)

### Question 2
Write and execute a SQL query to list all crimes that took place at a school. Include case number, crime type and community name.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q2.png)

### Question 3
Write and execute a SQL statement to create a view showing the columns listed in the following table, with new column names as shown in the second column.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q3.png)

### Question 4
Write the structure of a query to create or replace a stored procedure called UPDATE_LEADERS_SCORE that takes a in_School_ID parameter as an integer and a in_Leader_Score parameter as an integer. Don't forget to use the #SET TERMINATOR statement to use the @ for the CREATE statement terminator.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q4.png)

### Question 5
Inside your stored procedure, write a SQL statement to update the Leaders_Score field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID to the value in the in_Leader_Score parameter.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q5.png)

### Question 6
Inside your stored procedure, write a SQL IF statement to update the Leaders_Icon field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID using the following information.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q6.png)

### Question 7
Write a query to call the stored procedure, passing a valid school ID and a leader score of 50, to check that the procedure works as expected.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q7.png)

### Question 8
Update your stored procedure definition. Add a generic ELSE clause to the IF statement that rolls back the current work if the score did not fit any of the preceding categories.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q8.png)

### Question 9
Update your stored procedure definition again. Add a statement to commit the current unit of work at the end of the procedure.
![alt text](https://github.com/JeffreyChiu1998/DataScienceWorks/blob/main/CourseraDataScienceProject/SQLHonors/Images/Q9.png)
