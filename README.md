Assignment-1
NAME: SAI KEERTHI THUNGAPATI ID#: 700763831

1)Write a program that takes two strings from the user: first_name, last_name. Pass these variables to fullname function that should return the (full name). o For example: ▪ First_name = “your first name”, last_name = “your last name” ▪ Full_name = “your full name” o Write function named “string_alternative” that returns every other char in the full_name string. Str = “Good evening” Output: Go vnn

Solution: This Python function asks the user for their first and last name, concatenates those inputs to create the full name, and then returns the amended fullname with all other characters picked. The first and last names are joined with a space between them using the fullname function. Using Python's slicing syntax [::2], the string_alternative method slices the string to return every other character. The whole name is printed, the string with alternate characters is shown, and user input is gathered in the main function. For instance, if you input "sai" and "keerthi" the result will be "Full name: saikeerthi" and then "String with alternate characters: sierh".


2)Write a python program to find the wordcount in a file (input.txt) for each line and then print the output. o Finally store the output in output.txt file. Example: Input: a file includes two lines: Python Course Deep Learning Course Output: Python Course Deep Learning Course Word_Count: Python: 1 Course: 2 Deep: 1 Learning: 1

Sloution: In Google Colab, this code generates an input.txt file with the lines "Python Course" and "Deep Learning Course." Then, it defines a function called word_count, which reads the input.txt file, uses Python's Counter to count the instances of each word, and then writes the word count results and the original text into an output.txt file. The code computes the word frequencies and appends them to output.txt after first writing the lines from the input file to the output file. Lastly, it shows the content of output.txt and prints the word count.


3)Write a program, which reads heights (inches.) of customers into a list and convert these heights to centimeters in a separate list using:

Nested Interactive loop.
List comprehensions Example: L1: [150,155, 145, 148] Output: [68.03, 70.3, 65.77, 67.13]

Solution: This Python code uses both list comprehension and a nested loop to convert a list of client heights from inches to centimeters. The user is invited to enter the number of heights and the heights themselves in inches within the main() method. The conversion is subsequently carried out by the software using the function inches_to_centimeters_nested() in a loop, where each height is multiplied by 2.54 and rounded to two decimal places. Then, with a more condensed list comprehension, it uses inches_to_centimeters_list_comprehension() to accomplish the same goal. For comparison, both results are printed. The application shows an error message if the input is invalid.
