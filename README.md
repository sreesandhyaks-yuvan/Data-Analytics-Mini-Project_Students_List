# Data-Analytics-Mini-Project_Students_List
Students Performance &amp; Placement Analysis Dashboard
Removing duplicates:- Select the complete dataset- click the Data tab- Select Remove Duplicates- select Id column and then Click OK. Result no duplicates founded.
Handling missing values:- Press Ctrl + G- Click Special-Select Blanks and then Click OK.
No field found, highlighted only one blank cell in Year of experience column. Which iwas replaced by Find & Replace option.
Creating calculated fields (if required):- Created Column and given formula- 1. Gpa Level
=IF(J2=3.6,"Average",IF(J2>=3.6,"High","Low")) ,(If GPA is exactly 3.6 → Average, If GPA is greater than or equal to 3.6 (after the first condition) → High,If GPA is below 3.6 → Low)
2.	Salary Level=IF(I2>63000,"High Salary",IF(I2>=57000,"Medium Salary","No Salary"))
[Salary above ₹63,000 ‘ High Salary’, Salary between ₹57,000 and ₹63,000 ‘Medium Salary’Salary below ₹57,000 ‘No Salary’]
Filtering and sorting:-  Go to Data → Sort-Select the student name column and Choose ascending order.
Creating Pivot Tables (if required):_Selected the range and given name as Student_list, thus made as a table . Then select the table and then select Pivot option


