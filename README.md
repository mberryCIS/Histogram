This project is a simple C++ program that generates a histogram based on user-provided data values. The histogram displays each data value as a series of characters (- and *), with * appearing at every 5th position in the seque

Features

Accepts a customizable number of data items.

Displays each data value as a row in a histogram.

Uses dashes (-) for positions not divisible by 5.

Uses asterisks (*) for every 5th position.


How It Works

Input the Number of Data Items:

The user specifies how many data items they want to input.

Enter Data Values:

The program collects the specified number of data values, storing them in a vector.

Generate and Display Histogram:

Each value in the vector is represented as a row in the histogram.

For each row:

Dashes (-) fill most positions.

Asterisks (*) are displayed at every 5th position

Example Usage

Input:
```bash
How many data items do you have? 3
Enter data item 1: 7
Enter data item 2: 10
Enter data item 3: 3
```
Output:
```bash
Displaying Histogram
------*
----*-*---*
---
```
Explanation:

First Row (7): 6 dashes and 1 asterisk.

Second Row (10): Alternates between 4 dashes, 1 asterisk, 4 dashes, and 1 asterisk.

Third Row (3): Contains 3 dashes only.


How to Compile and Run

Save the program as histogram.cpp.

Open a terminal and navigate to the file's directory.

Compile the program using a C++ compiler, e.g., g++:
