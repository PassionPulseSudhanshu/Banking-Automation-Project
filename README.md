Banking-Automation-Project
Welcome to the Banking Automation System, a Python-based GUI application for efficient and secure banking operations.

Overview

This project offers a user-friendly interface with features such as account management, password recovery, transaction history, and more.

Key Features

- User-friendly interface
- Account operations (login, new account)
- Password recovery via email OTP
- Transaction history tracking
- Profile customization

Banking System Python Project Overview
1. User Interface using Tkinter:
The graphical user interface (GUI) of the banking system is implemented using Tkinter, a popular Python GUI toolkit.
Different screens are designed for actions like user registration, login, and OTP verification.
2. User Registration:
Users can create accounts by providing necessary details such as name, email, password, etc.
The registration information is stored in a SQLite database.
3. Login System:
Registered users can log in using their account credentials.
The login process involves checking the entered credentials against the stored data in the SQLite database.
4. Password Recovery:
In case users forget their passwords, there is a password recovery mechanism.
The user needs to enter their account number and email to receive an OTP for verification.
5. OTP Generation and Sending:
OTPs are randomly generated four-digit codes.
The system attempts to send the OTP to the user's email using Gmail.
6. Email Configuration for OTP Sending:
There is an attempt to configure email settings for sending OTPs.
The project uses Gmail for sending emails.
7. Issues Faced and Solutions:
There are issues related to file paths and missing files (default.jpg).
The code has been modified to fix these issues.
Additionally, there was an issue related to sending OTP emails, which might be due to the configuration of the Gmail account.
8. Recommendations for Email Configuration:
Suggested enabling "Less secure app access" in the Gmail account settings.
Encouraged using an App Password for increased security in email authentication.
9. Code Modification for Email Sending:
Provided a code snippet demonstrating how to modify the script to use an App Password for sending OTP emails.
10. Final Remarks:
The project showcases fundamental concepts of GUI development, database management, and email communication in Python.
The developer is encouraged to review and update email configurations for reliable OTP sending.
This project not only serves as a practical application of Python programming skills but also introduces concepts relevant to real-world scenarios in banking and secure communication.




 
 
