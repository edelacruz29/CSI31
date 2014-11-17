CSI31
=====

Here We Will Share work and Collaborate on our projects

CSI 31			Assignments for Weeks 8 & 9


	1.  Complete the program that we did in class that computes the sum of the squares in a list.  I e-mailed you the shell.  You need to write the code for the functions squareEach and sumList.  I have attached a program that does the toNumbers function that we did in class. [p. 198, 11,12,13]

2.  [Ch 7 #1, p. 230]   Many companies pay time-and-a-half for any hours worked above 40 in a given week.  Write a program to input the number of hours worked and the hourly rate and calculate the total wages for the week. 
 
	a) Do this for one employee and print out the person’s weekly pay.  

	b) Do this in a loop and accumulate the total payroll for the week -- [payroll = 0 # 
	    initialize it]; as you calculate each person’s pay, add it to payroll [payroll = payroll + 
	    pay].
	
3.  [Ch 7 # 14, p. 232]  Do Programming Exercise from Ch 4, but add a decision to handle the case where the line does not intersect the circle. 

4. [Ch 7 # 15, p. 232]  Do Programming Exercise 8 from Ch 4 , but add a decision to prevent the program from dividing by zero if the line is vertical.

Note:  Most of you have already done 1, 3 and 4.  If not, see the attachment for Weeks 5 & 6.


Variation on #2.  I will send you a file named ‘namesWages.txt’.  For each employee there is a line which contains:  Last Name, First Name, hourly wage, and number of hours worked for the week. (Note that the delimiter between the fields is a blank.  This is because the decimal point was confusing the read command.)

Using the model on page 157, open ‘names-wages.txt’ for reading in the data and open ‘payroll.txt’ for writing.  In the input file, each piece of data is a string, so in order to calculate the pay, both have to be converted to a number [wage = eval(wave) and hours = eval(hours)].  The calculated weekly pay is a number which has to be converted to a string [str(pay) will work]. Each employee should have a line in the output file with the following information:   Last Name, First Name, and weekly salary. Construct a line for the output file delimiting each field with a blank between the items [oline = lastName + ‘ ‘+ firstName + ‘ ‘ + str(pay) + ‘\n’]. Write this to the file.

At the end, print out the total payroll for the week, appropriately formatted with a $ and two decimal places.

5. Write a program to print out the Syracuse sequence for any natural number. [p. 263 #4]

