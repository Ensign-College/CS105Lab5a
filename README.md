Lab 5a
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section of the Class Resources module), or the instructor in class. Follow the CS 105 Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Use a FOR loop
-   Understand when it's best to use a FOR loop and when it's best to use a WHILE loop
-   Use the modulus ( % ) operator.

Structure:
==========

Create the following structure in Eclipse for this lab.

**Package Name:** week5\
**Class Name:** Lab5a

Program: Whole Numbers Divisible by X
=====================================

In this program you will ask the user for three whole numbers (integers). Use three input validation loops to ensure that all three numbers entered by the user are integers.  Your program will then output every number between the first number and the second number (inclusive of both) that is divisible by the third number. Remember that when a number is divisible by X, that means that it can be divided by X and the result is an exact whole number (no remainder).

After the program has finished, ask the user if they would like to play again. Use input validation to ensure the user answers with a Y or N. Keep the program running in an infinite loop until the user indicates they want to quit.

Evaluation walk through:
========================

Let's say a user entered the numbers 7, 15 and 5. Let's determine which numbers would be output.

Evaluate all numbers between and including 7 and 15

-   evaluate 7 - not divisible by 5.
-   evaluate 8 - not divisible by 5.
-   evaluate 9 - not divisible by 5.
-   evaluate 10 - divisible by 5! Print this number!
-   evaluate 11 - not divisible by 5.
-   evaluate 12 - not divisible by 5.
-   evaluate 13 - not divisible by 5.
-   evaluate 14 - not divisible by 5.
-   evaluate 15 - divisible by 5! Print this number!

In this case the program would have only displayed two numbers (10 and 15).

Key program requirements:
=========================

-   Your program must evaluate all numbers between and including the first number and the second number specified by the user.
-   You program must only output numbers that are exactly divisible by the third number.
-   Your program must perform input validation on all three numbers entered by the user to ensure they are all integers.
-   Your program must perform input validation on the "Play again (Y/N)" question to ensure the answer entered by the user is either a "Y" or "N".
-   Your program must use while loops for input validation and a for loop to evaluate which numbers are divisible by the third number.
-   Submit the following .java file:
    -   Lab5a.java

Example Run:
============

*In this program, we will display a series of numbers divisible by an integer specified by the user.*\
*You will ask the user for the starting number, the ending number and the integer to be considered.*

*Enter the starting number: seven*\
*Error: Please enter a whole number.*

*Enter the starting number: 7*\
*Enter the ending number: 45*\
*Enter the test number: 5*\
*Here are the numbers between 7 and 45 that are divisible by 5:*\
*10*\
*15*\
*20*\
*25*\
*30*\
*35*\
*40*\
*45*\
*Would you like to play again? sure*\
*Error: Please answer with a 'Y' or 'N'.*

*Would you like to play again? n*