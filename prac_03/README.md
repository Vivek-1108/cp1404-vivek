# Practical 03
# String Formatting in Python

## Overview
This project demonstrates string formatting in Python using both the `.format()` method and f-strings. It includes examples that showcase how to format strings and numbers, with a focus on readability and alignment.

## File Structure
- `string_formatting.py`: Contains examples of string formatting and a loop demonstrating power calculations.

## Code

```python
# string_formatting.py

# Example of string formatting using .format()
guitar = "Gibson L-5 CES"
price = 16036

# Using .format() to format the string
formatted_string = "{} for about ${:,.2f}!".format(guitar, price)
print(formatted_string)

# Using f-strings to produce the output
print(f"{guitar} for about ${price:,.2f}!")

# Using a for loop with f-string formatting
for i in range(11):
    result = 2 ** i
    print(f"2 ^ {i:>2} is {result:>5}")




**# Random Numbers in Python**

## Overview
This project demonstrates the use of the `random` module in Python to generate random numbers. It includes examples of generating random integers, random floats, and explains the use of various functions from the `random` module.

## File Structure
- `randoms.py`: Contains code that generates random numbers and explanations of the output.

## Code

The following code is included in `randoms.py`:

```python
import random

# Line 1: Generate a random integer between 5 and 20 (inclusive)
print(random.randint(5, 20))  # line 1

# Line 2: Generate a random number from the range 3 to 10, with a step of 2
print(random.randrange(3, 10, 2))  # line 2

# Line 3: Generate a random floating-point number between 2.5 and 5.5
print(random.uniform(2.5, 5.5))  # line 3

# Generate a random number between 1 and 100 inclusive
random_number = random.randint(1, 100)
print(random_number)

# Capitalist Conrad Stock Price Simulator

## Overview
This project simulates the daily price changes of a volatile stock. The stock price starts at $10.00 and can either increase by up to 17.5% or decrease by up to 5% each day. The simulation continues until the stock price rises above $100.00 or falls below $1.00. The results are recorded in a text file.

## File Structure
- `capitalist_conrad.py`: Contains the code for the stock price simulator.

## Code Explanation

The following constants are defined at the beginning of the program:
- `STARTING_PRICE`: The initial price of the stock, set to $10.00.
- `MAX_PRICE`: The maximum allowable price of the stock, set to $100.00.
- `MIN_PRICE`: The minimum allowable price of the stock, set to $1.00.
- `MAX_INCREASE`: The maximum percentage increase allowed, set to 17.5%.
- `MAX_DECREASE`: The maximum percentage decrease allowed, set to 5%.
- `FILENAME`: The name of the output file where the results will be saved.

### How It Works
1. The program initializes the stock price and a counter for the number of days.
2. It opens a file for writing to record the stock price changes.
3. A loop runs until the stock price is outside the allowable range.
4. Each day, the program randomly decides whether to increase or decrease the price and calculates the new price accordingly.
5. The price for each day is printed to the output file.
6. The file is closed once the simulation ends.

## Usage
1. Clone the repository or download the `capitalist_conrad.py` file.
2. Ensure you have Python installed on your machine.
3. Navigate to the directory containing the `capitalist_conrad.py` file.
4. Run the script using the command:

   ```bash
   python capitalist_conrad.py

# Integer Input Validation Program

## Overview
This program prompts the user to enter an integer and handles invalid inputs gracefully. If the user enters a non-integer value, the program will catch the exception and prompt the user to try again.

## File Structure
- `exceptions_to_complete.py`: Contains the code for the integer input validation program.

## Code Explanation

### Functionality
- The program defines a function `get_integer()` that:
  - Continuously prompts the user for input until a valid integer is entered.
  - Uses a `try-except` block to catch `ValueError` exceptions when the input cannot be converted to an integer.
  - Prints an error message if the input is invalid and asks the user to try again.

### Main Execution
- The main part of the program calls the `get_integer()` function and prints the valid integer entered by the user.

## Usage
1. Clone the repository or download the `exceptions_to_complete.py` file.
2. Ensure you have Python installed on your machine.
3. Navigate to the directory containing the `exceptions_to_complete.py` file.
4. Run the script using the command:

   ```bash
   python exceptions_to_complete.py


# Password Checker Program

## Overview
This program validates the strength of a password based on specific criteria. It checks whether the password contains at least one digit, one lowercase letter, one uppercase letter, and optionally, one special character. The user is prompted to enter a password until a valid one is provided.

## File Structure
- `password_checker.py`: Contains the code for the password validation program.

## Code Explanation

### Constants
- `MIN_LENGTH`: Minimum length of the password (default is 5).
- `MAX_LENGTH`: Maximum length of the password (default is 15).
- `REQUIRE_SPECIAL_CHAR`: Boolean indicating if special characters are required (default is `False`).
- `SPECIAL_CHARACTERS`: A string containing valid special characters.

### Functionality
- The program defines a function `is_valid_password(password)` that:
  - Checks if the password meets the length requirements.
  - Validates the presence of at least one lowercase letter, one uppercase letter, and one digit.
  - Optionally checks for special characters if required.

### Main Execution
- The main part of the program continuously prompts the user for a password until a valid one is entered, providing feedback on the validity of the entered password.

## Usage
1. Clone the repository or download the `password_checker.py` file.
2. Ensure you have Python installed on your machine.
3. Navigate to the directory containing the `password_checker.py` file.
4. Run the script using the command:

   ```bash
   python password_checker.py


# File Handling in Python

## Overview
This program demonstrates various file handling techniques in Python, including writing to files and reading from them using different methods. It covers the use of `open()`, `read()`, `readline()`, `readlines()`, and iterating over a file.

## File Structure
- `files.py`: Contains the code for reading from and writing to text files.

## Code Explanation

### Tasks Implemented

1. **Write User's Name**:
   - The program prompts the user to enter their name and writes it to a file named `name.txt`.

2. **Read and Greet**:
   - It reads the name from `name.txt` and prints a greeting in the format `Hi [Name]!`.

3. **Sum of First Two Numbers**:
   - A file called `numbers.txt` is created with three specified numbers. The program reads the first two numbers, adds them together, and prints the result.

4. **Total of All Numbers**:
   - The program reads through all lines in `numbers.txt`, sums all the numbers, and prints the total.

## Usage
1. Clone the repository or download the `files.py` file.
2. Ensure you have Python installed on your machine.
3. Navigate to the directory containing the `files.py` file.
4. Run the script using the command:

   ```bash
   python files.py
