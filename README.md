
# Password Generator
## Overview
The Password Generator is a Python application that creates random, secure passwords based on user-defined criteria. It supports three levels of password strength and provides options to save generated passwords along with associated usernames and sites to a file.

## Features
Customizable Password Length: Specify the desired length of the generated password.
Adjustable Password Strength: Choose from three strength levels:
Basic: Uppercase and Lowercase letters.
Medium: Uppercase, Lowercase letters, and Numbers.
Strong: Uppercase, Lowercase letters, Numbers, and Symbols.
Clipboard Integration: Automatically copies the generated password to the clipboard.
Password Saving: Optionally save generated passwords with associated usernames and sites to a file.
## Requirements
Python 3.12.4
pyperclip library for clipboard functionality
To install pyperclip, run:
pip install pyperclip
### Usage
Run the Program:
python password_generator.py
### Follow the Prompts:
Enter the desired password length.
Choose the password strength (1 for Basic, 2 for Medium, 3 for Strong).
Optionally provide a username and site for saving the password.
### Password Generation:

The program will display the generated password.
The password will be copied to the clipboard automatically.
You will be asked if you want to save the password. If you choose to save, provide the username and site.
### View Saved Passwords:
Saved passwords will be appended to passwords.txt in the same directory as the script.
## Code Overview
print_welcome_message(): Prints a welcome message when the program starts.
get_password_length(): Prompts the user for the length of the password.
get_password_strength(): Asks the user to select the strength of the password.
get_username(): Prompts the user for a username to associate with the password.
get_site(): Asks the user for the site for which the password is intended.
generate_password(length, strength_choice): Generates a password based on the length and strength choice.
save_password_to_file(username, site, password): Saves the password along with the username and site to passwords.txt.
Contributing
Feel free to submit issues or pull requests if you have suggestions for improvements or encounter any problems.
