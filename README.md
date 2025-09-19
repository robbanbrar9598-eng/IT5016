# IT5016
Assignment
IT5016
Assessment 3: Programming Principles and Concepts
NAME:-  Robbandeep Singh Brar
Student :- 20251168

 
Overview
Int this project a software development company that wants a purchase requisition system developed for its staff clients.
This will handle requisition IDs. Purchase requests would be submitted by staff, and the request will be approved/not approved by a manager/supervisor based on some conditions.

Get hub URL
https://github.com/robbanbrar9598-eng/IT5016.git

Features and principles
1.	Reusability: 
2.	Readability and Commenting:
3.	K.I.S.S Principle (Keep It Simple, Stupid) 
4.	D.R.Y Principle (Don’t Reapeat Yourself)
5.	Structured Programming
6.	Single Responsibility Principle

Functions
I have used some functions in this assignment
The following are the functions
•	Staff_info()
•	Requisition_total()
•	Requisition_approval()
•	Display_requisition()

1.	Details of the functions
•	Staff_info()
 This function collects the data from the staff member, like 
•	Staff name
•	Staff ID 
•	Date
•	Requisition ID 
This function also creates a unique ID counter from 10000 and increments by 1 whenever a new staff member is added. It also returns the values input and requisition ID.
For example 
:if choice == "yes"  or choice == "no":          
                            Break
status = "Pending"     
    approval_ref = None  in this codes I have used requisitionand it runs perfectly



•	Requisition_total(   )
In this function, the staff member will input the items' values, and will return the sum of the total items for all the requisitions. 
  total = 0  is variable where DRY principle is  used 
•	Requisition approval :- this function is based on the deicion for approval and pending , which condition is based on the requcisition_total. If the total I <500 than it will be autimatcialy approved if it is .500 then it will show pnding


2.	How this code works?
i.	Staff will enter their required details like:- staff_id, staff_name, date, etc.
ii.	After filling in details each staff member needs to add their needed item and their price 
iii.	To get total price of the items requisition total will do sumup.
iv.	After getting the total value manager will under the the decision if, its above the 500 manager can pending or can reject it, and if below 500 it will automatically approved 
v.	At the end of the function summaries ,and show with the staff_info,requisitions id , total etc.

Limitations
There are few limitation in this coding , below are the following 
•	Errors:- If the user inputs the wrong value the code is crashed and need to start getting details from beginning 
•	Loop:- In the staff_info function loop has one error. To break the loop only I should use yes, but if I write no, the code is also breaked.

Future Implementations 
•	Valid Input:- I will create some parameters to control the wrong entries, means where ever user will put invalid value terminal will show error or will repear it again.
•	Code changes:- I will change the yes and no condition loop in staff_info function, by implementing , new rule that after yes loop will again run ,but if no loop will break there.

Learning out come :
a.	This will help to understand the Kiss , dry, readability, commenting
b.	How to handle user input values
c.	Learn what is while loop
d.	 How to think critically and future implementation of system. 


