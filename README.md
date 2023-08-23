Objective:
The purpose of this assignment is to test your understanding of exception handling and File I/O operations in Java. You are encouraged to apply the best practices discussed during the lecture.

## Problem 1: Basic Exception Handling
Write a program that prompts the user to input an integer. If the user enters something that isn't an integer, the program should handle the error and prompt the user again until a valid integer is received.

Bonus: Handle multiple types of exceptions and provide different messages for each.

## Problem 2: File Reading with BufferedReader
You are provided with a text file named students.txt. Each line of the file contains the name of a student.

Write a program to read and display the contents of the file.
Count and print the total number of students listed in the file.

## Problem 3: File Writing with Exception Handling
Write a program that prompts the user to enter sentences. Each sentence entered should be written to a file named user_input.txt. After writing each sentence, ask the user if they wish to continue. If they choose not to, stop the program.

Make sure to handle exceptions appropriately, especially focusing on:

Handling the situation where the file can't be created or opened for writing.
Handling interruptions during writing.

## Problem 4: Reading Numbers from a File
Given a file named numbers.txt, which contains a list of numbers (one number per line):

Write a program to read the file.
Calculate and display the sum and average of the numbers.
If the file contains any non-numeric data, handle the exception and skip to the next line without crashing the program.

## Problem 5: Try-with-Resources Challenge
Re-write the solutions to Problems 2 and 3 using the try-with-resources statement to ensure efficient resource management.

## Bonus Problem: Custom Exception
Write a program that prompts the user to enter their age. If the age entered is negative, throw a custom exception named InvalidAgeException. Handle the exception and display an appropriate message to the user.

