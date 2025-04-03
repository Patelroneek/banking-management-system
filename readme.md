Bank Account Management System

Overview

This is a simple Bank Account Management System implemented in C. The program allows users to create an account, log in, transfer money, and check their balance. The data is stored in files for persistent storage.

Features

User Registration: Create a new bank account with personal details.

Login System: Secure authentication using a username and password.

Money Transfer: Transfer money between users.

Balance Check: View transaction history and account balance.

Logout Feature: Securely log out from the system.

Installation and Compilation

Requirements

A C compiler (e.g., GCC, MinGW for Windows)

Windows OS (Program uses Windows-specific functions like gotoxy and SetConsoleCursorPosition)

Compilation

To compile the program, use the following command:

gcc bank_system.c -o bank_system.exe

Then, run the executable:

./bank_system.exe

Usage

Run the program.

Choose from the main menu:

Create a Bank Account: Register a new user.

Sign In: Log in to an existing account.

Exit: Quit the program.

After logging in, choose actions such as:

Checking balance

Transferring money

Logging out

File Storage

username.txt: Stores user details.

mon.txt: Stores transaction history.

Known Issues

The program uses getch() for password input, which may not work on some compilers.

Data security is minimal as passwords are stored in plaintext.

The program is Windows-dependent due to console cursor positioning functions.

Future Improvements

Encrypt passwords for better security.

Implement cross-platform compatibility.

Improve user interface and error handling.

Author

Developer: Naman Kumar

License

This project is open-source and available for educational purposes.