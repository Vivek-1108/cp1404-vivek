# Practical 04
README.
# Python Code Projects

Author: Vivek Dobariya  

This repository contains a collection of Python programs designed to demonstrate various programming concepts, including list operations, file handling, user input, and random number generation. Each program is explained below with its purpose and usage instructions.

## Table of Contents
1. [Lists Warm-Up (`lists_warmup.py`)](#1-lists-warm-up)
2. [Accountant Annie (`total_income.py`)](#2-accountant-annie)
3. [Subject Reader (`subject_reader.py`)](#3-subject-reader)
4. [Basic List Operations (`list_exercises.py`)](#4-basic-list-operations)
5. [List Comprehensions (`list_comprehensions.py`)](#5-list-comprehensions)
6. [Quick Pick Lottery Generator (`quick_picks.py`)](#6-quick-pick-lottery-generator)

---

## 1. Lists Warm-Up
**File:** `lists_warmup.py`  
**Description:**  
This program demonstrates basic list operations in Python. It includes:
- Predicting the output of various list expressions.
- Verifying predictions by running the code.
- Modifying lists using indexing and slicing.

**How to Use:**
- Run the program to see the results of list operations.
- Modify the code to experiment with different list expressions.

---

## 2. Accountant Annie
**File:** `total_income.py`  
**Description:**  
This program calculates cumulative monthly income totals. It asks the user for the number of months, collects income inputs, and displays a formatted report showing the monthly income and cumulative total.

**How to Use:**
1. Run the program.
2. Enter the number of months.
3. Input the income for each month.
4. View the generated income report.

Example:
```
How many months? 3
Enter income for month 1: 1000
Enter income for month 2: 1500
Enter income for month 3: 2000

Income Report
-------------
Month  1 - Income: $   1000.00 Total: $   1000.00
Month  2 - Income: $   1500.00 Total: $   2500.00
Month  3 - Income: $   2000.00 Total: $   4500.00
```

---

## 3. Subject Reader
**File:** `subject_reader.py`  
**Description:**  
This program reads data from a file (`subject_data.txt`) containing subject details, processes it into a list of lists, and displays the subject details in a formatted manner.

**How to Use:**
1. Ensure the file `subject_data.txt` exists in the same directory as the program.
2. Run the program to see the formatted subject details.

Example `subject_data.txt` file:
```
CP1401,Dr. Smith,120
CP1404,Dr. Brown,95
CP1801,Dr. Green,80
```

Output:
```
CP1401 is taught by Dr. Smith and has 120 students
CP1404 is taught by Dr. Brown and has 95 students
CP1801 is taught by Dr. Green and has 80 students
```

---

## 4. Basic List Operations
**File:** `list_exercises.py`  
**Description:**  
This program performs two tasks:
1. Basic operations on a list of numbers, including finding the minimum, maximum, and average values.
2. A security checker that verifies if a username is in a predefined list.

**How to Use:**
- **Part 1:** Enter 5 numbers when prompted to see the calculations.
- **Part 2:** Enter your username to check if access is granted.

Example:
```
Number: 10
Number: 20
Number: 30
Number: 40
Number: 50
The first number is 10
The last number is 50
The smallest number is 10
The largest number is 50
The average of the numbers is 30.0

Enter your username: jimbo
Access granted
```

---

## 5. List Comprehensions
**File:** `list_comprehensions.py`  
**Description:**  
This program demonstrates the use of list comprehensions in Python. It includes examples of:
- Squaring numbers.
- Filtering even numbers.
- Finding numbers divisible by 3.
- Converting strings to uppercase.

**How to Use:**
- Run the program to see the output of each list comprehension.

Example Output:
```
[1, 4, 9, 16, 25]
[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48]
['HELLO', 'WORLD', 'PYTHON']
```

---

## 6. Quick Pick Lottery Generator
**File:** `quick_picks.py`  
**Description:**  
This program generates "quick pick" lottery tickets. Each ticket contains 6 unique random numbers between 1 and 45, displayed in ascending order. The user specifies how many tickets to generate.

**How to Use:**
1. Run the program.
2. Enter the number of quick picks you want.
3. View the generated lottery tickets.

Example:
```
How many quick picks? 3
 5 12 18 22 35 44
 1  3 15 23 30 45
 2  8 19 25 34 41
```

---

## Git Repository Maintenance
To maintain this repository properly:
1. **Commit Frequently:** Commit changes after completing each program with meaningful commit messages.
   ```
   git add .
   git commit -m "Completed lists_warmup.py"
   ```
2. **Use Branches:** Create a new branch for each feature or program.
   ```
   git checkout -b feature/total_income
   ```
3. **Push Regularly:** Push changes to the remote repository.
   ```
   git push origin feature/total_income
   ```
