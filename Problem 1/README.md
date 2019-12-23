## Problem 1
* The user has a file that is made up of short (less than 1000 character) strings, each on a different line (assume any common character or character combination that means a newline to someone might be used interchangeably in this file). Most of these strings will be preceded by numbers, i.e. “2 Steaks”, “10 Chicken Wings”, “343GuiltySparks”. Accept the file from the user and return them a file with the same items sorted first by the numeric value of any leading number (2 < 10 < 343) and then alphabetically for the rest of the string.

* INSTRUCTIONS:
* Open the AlphaNumSort.ipynb in a jupyter notebook.
* Execute the cells in the notebook one by one when prompted to enter the input file name place the file in the same folder as this notebook.
* When all the cells have been executed your_file.txt is generated as the final sorted file.

* CODE EXPLANATION:
* The code is written in python and uses regular expression module.
* It first takes the input file from the user and places all the strings in each line in a file to list.
* It then does a for loop on the list and the regular expression is used on each element of the list and the numbers and alphabets are taken into tuples as values in aa dictionary.
* Then using the sorted() function, it sorts the dictionary based on these multiple values in tuple and final sorted list is generated.
* This sorted list is written into your_file.txt file.