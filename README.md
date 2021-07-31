# Dynamic-Website
This is a Dynamic Website Made for an Imaginary Company Status Infotainment, which wants to recruit some fresh graduates who are 
technically efficient in JAVA/Python for their ongoing projects. For this, they want to check their 
technical skills by giving them a scenario on which the Web Platform for which they have to 
submit the code online. 
For this, they want to create a web application in which a user can register by entering his/her 
name, email, mobile number, highest qualification, etc. After registering, the user shall login 
using his/her email and password. The user is provided a unique job application number, and a 
Problem statement for which he/she has to code on Java/Python in the text area provided. 
He/She has to choose the language in which he/she wants to code from a drop down box. On 
clicking the submit button, the code entered by the user is saved on the server as a file with the 
name JOB<application_no> and the extension is either .java or .py as the case may be. For 
example, if the job application number is 786, and the code is written in python, the file should 
be saved as JOB786.py on the server.
Also, there are at least 20 predefined Problem statement scenarios and the user is given a 
scenario on the basis of his/her job application number. The logic of providing the Problem 
statement is as follows:
1. Each problem is saved in a separate file named 1.txt, 2.txt, and so on to 20.txt.
2. The job application number is divided by 20 and the remainder is stored. Then 1 is added to 
the remainder to find the name of the file from which the Problem statement is to be fetched.
3. The contents of the file are then displayed on the browser.
