# Practical 02
# temperature.py
"""Temperature Conversion Program"""

def celsius_to_fahrenheit(celsius):
    """Convert Celsius to Fahrenheit."""
    return (celsius * 9/5) + 32

def fahrenheit_to_celsius(fahrenheit):
    """Convert Fahrenheit to Celsius."""
    return (fahrenheit - 32) * 5/9

def main():
    """Main function for temperature conversions."""
    celsius = float(input("Enter temperature in Celsius: "))
    fahrenheit = celsius_to_fahrenheit(celsius)
    print(f"{celsius}°C is {fahrenheit}°F")

    fahrenheit = float(input("Enter temperature in Fahrenheit: "))
    celsius = fahrenheit_to_celsius(fahrenheit)
    print(f"{fahrenheit}°F is {celsius}°C")

main()
"""Password Stars Program"""

# Constants
MIN_PASSWORD_LENGTH = 5

def main():
    """Main function to run the password check program."""
    password = get_password()
    print_asterisks(password)

def get_password():
    """Function to get a valid password from the user."""
    password = input("Enter a password (minimum length of {}): ".format(MIN_PASSWORD_LENGTH))
    while len(password) < MIN_PASSWORD_LENGTH:
        print("Password is too short. Try again.")
        password = input("Enter a password (minimum length of {}): ".format(MIN_PASSWORD_LENGTH))
    return password

def print_asterisks(password):
    """Function to print asterisks based on the password length."""
    print('*' * len(password))

main()

(2)"""Score Menu Program"""
def get_valid_score():
    """Get a valid score from the user (0-100)."""
    score = -1
    while score < 0 or score > 100:
        score = float(input("Enter a valid score (0-100): "))
    return score

def evaluate_score(score):
    """Evaluate the score and return the result."""
    if score >= 85:
        return "Excellent"
    elif score >= 50:
        return "Passable"
    else:
        return "Bad"

def show_stars(score):
    """Print stars based on the score."""
    print('*' * int(score))

def main():
    """Main menu function."""
    score = get_valid_score()
    
    while True:
        print("\nMenu:")
        print("(G)et a valid score")
        print("(P)rint result")
        print("(S)how stars")
        print("(Q)uit")
        
        choice = input("Choose an option: ").upper()
        
        if choice == 'G':
            score = get_valid_score()
        elif choice == 'P':
            result = evaluate_score(score)
            print(f"Your score is {result}")
        elif choice == 'S':
            show_stars(score)
        elif choice == 'Q':
            print("Farewell!")
            break
        else:
            print("Invalid choice, please try again.")

main()


(3)"""Score Evaluation Program"""

def evaluate_score(score):
    """Evaluate the score and return the result."""
    if score >= 85:
        return "Excellent"
    elif score >= 50:
        return "Passable"
    else:
        return "Bad"

def main():
    """Main function to get user score and print result."""
    score = float(input("Enter your score (0-100): "))
    result = evaluate_score(score)
    print(f"Your score is {result}")

main()
(4)"""Password Stars Program"""

# Constants
MIN_PASSWORD_LENGTH = 5

def main():
    """Main function to run the password check program."""
    password = get_password()
    print_asterisks(password)

def get_password():
    """Function to get a valid password from the user."""
    password = input("Enter a password (minimum length of {}): ".format(MIN_PASSWORD_LENGTH))
    while len(password) < MIN_PASSWORD_LENGTH:
        print("Password is too short. Try again.")
        password = input("Enter a password (minimum length of {}): ".format(MIN_PASSWORD_LENGTH))
    return password

def print_asterisks(password):
    """Function to print asterisks based on the password length."""
    print('*' * len(password))

main()
