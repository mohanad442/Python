# Lab 1

1- Special Calculator
Design a small application that keeps asking the user 3 choices:
- Enter 1 to sum integers from 1 to N
- Enter 2 to evaluate simple 2 numbers expression (e.g. 2 + 3)
Expect 3 items. Operations are: + - * / // **
Enter 3 to end the program
The user should input value from 1 to 3
Otherwise, inform that this is invalid and try again
Take proper input from the user and compute the answer
See next console simulation

2- Read an integer N: print all numbers <= N that satisfy the following property
- Either number is divisible by 8 or divisible by both 4 or 3

3- Read an integer N: print the first N numbers that are multiple of 3 but not multiple of 4

ex-> input: 11
     output: 3 6 9 15 18 21 27 30 33 39 42

Notice-> 12 is divisible by both 3 and 4 so excluded
------------------------------------------------------------------
# Lab 2

1- create two lists then Iterate both lists simultaneously

2- Concatenate two lists index-wise 
	-> ['a','b'] , ['c','d']
	output - > ['ac' , 'bd']

3- Remove empty strings from the list of strings using filter function

4- Compute avarge of row and column using function and select if user want row or column

5- create function take list and create new list check if it sublist from it or not

6- create function to check if string is Palindrom or not
	ex -> madam 
	      left = right
-------------------------------------------------------------
# Lab 3

1- Using a list comprehension, create two new list called "newlist_1","newlist_2" out of the list "numbers", 
which contains only the positive numbers and negative number from the list, as integers.


2- Write program to generate and print a dictionary that contains a number (between 1 and n) in the form (x, x*x). Go to the editor
	Sample Dictionary ( n = 5) :
	Expected Output : {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}

3- Write a program to merge two Python dictionaries

4- Write a function to generate all pairs from two lists

5- rewrite this function using list comp.

6- convert 2D list to 1D -> flatten list and do it using list comp.

7- write function sort number don't use any built in function

8- write function to get max pair in list
	ex-> lst =[2,15,10,3,50]
	out-> 15+50 = 65
then get min pair  

9- write function to replace min and max inplace 
	ex -> lst = [4,1,3,10,8,10,10]
	out-> [4,10,3,1,8,1,1]
-------------------------------------------------------------
# Lab 4

1- Write a python program to find the longest word in file

2- Write a Python program to count the frequency of words in a file

--------------------------------------------------------------
# Lab 5 (Problem solving)

## Question 1

Write a function called underline that takes a file name as a parameter and that prints the words one per line with certain words underlined.  

The words to be underlined all begin with a period.  

The period should not be printed.  

You should print the text that follows the period on a line by itself followed by a line of alternating dashes and commas equal in length to the text that follows the period. 


## Question 2 (uses the attached steps.txt file)

A Personal Fitness Tracker is a wearable device that tracks your physical activity, calories burned, heart rate, and so on. One common physical activity that most of these devices track is the number of steps you take each day. 
The steps.txt file contains the number of steps a person has taken each day for a year. There are 365 lines in the file, and each line contains the number of steps taken during a day. (The first line is the number of steps taken on January 1st, the second line is the number of steps taken on January 2nd, and so forth.) Write a program that:
•	Reads the file, then displays the average number of steps taken for each month. 
•	(The data is from a year that was not a leap year, so February has 28 days.



1- A painting company has determined that for every 112 square feet of wall space, one gallon of paint and eight hours of labor will be required. The company charges $35.00 per hour for labor. 

Write a program that asks the user to enter the square feet of wall space to be painted and the price of the paint per gallon. 
The program should display the following data: 
- The number of gallons of paint required 
- The hours of labor required 
- The cost of the paint 
- The labor charges 
- The total cost of the paint job


## Question 3
A painting company has determined that for every 112 square feet of wall space, one gallon of paint and eight hours of labor will be required. The company charges $35.00 per hour for labor. 

Write a program that asks the user to enter the square feet of wall space to be painted and the price of the paint per gallon. The program should display the following data: 
- The number of gallons of paint required 
- The hours of labor required 
- The cost of the paint 
- The labor charges 
- The total cost of the paint job 


## Question 4

Write a code that generate 200 random numbers between -510 and 275 then adds those numbers to a text file. Repeat that step 4 time (you end up with a file that have 4 lines each has 200 numbers separated by spaces)
-	Read the data from the file line by line. Each integer value must be: -500 <= value <= 270
-	If a value was entered outside that range raise an exception, print error message to the output then continue processing the rest of the numbers.
-	Find the value that repeated the most number of times in each line.
-	If there are many solutions: find the smallest value.
-	Find the maximum number in all lines
-	Find the minimum number in all lines


## Question 5

Implement function: def sort_different_types(lst):
- It takes a list of different data types (int, float, string, list, tuple) 
- Return a list:
- For every data type, group, and sort from small to large
- Within data types: Order them based on the order of the list (int comes first? Be first)
- Assumption: provided lists or tuples will be comparable.
