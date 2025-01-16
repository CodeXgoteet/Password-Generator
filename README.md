# Password Generator

A secure and user-friendly GUI-based password generator built with Python and Tkinter. This tool allows users to create strong passwords of customizable length and stores them in a local SQLite database for future reference.

## Features
- **Customizable Password Length**: Generate passwords of user-defined lengths.
- **Randomized Secure Passwords**: Includes uppercase, lowercase, special characters, and numbers.
- **Username Integration**: Each password is associated with a unique username.
- **SQLite Database**: Stores usernames and their corresponding passwords securely.

## Requirements
- Python 3.x
- Tkinter (comes pre-installed with Python)
- SQLite3 (comes pre-installed with Python)

## How to Use
1. Enter your username in the "Enter User Name" field.
2. Specify the desired password length (minimum 6 characters).
3. Click "GENERATE PASSWORD" to create a strong password.
4. Review the generated password in the provided field.
5. Click "ACCEPT" to save the username and password to the database.
6. Use "RESET" to clear all fields for new entries.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/password-generator.git
## Navigate to the project directory
cd password-generator

## Run the application
python Password.py

## Project Structure
Password.py: The main Python script containing the GUI, logic, and database integration.
users.db: SQLite database created dynamically to store user credentials.

## Screenshots
![Screenshot 2025-01-16 170048](https://github.com/user-attachments/assets/9ded379c-eaea-4a83-b234-5158a2625415)
![Screenshot 2025-01-16 170018](https://github.com/user-attachments/assets/ab503f9f-1772-45a5-9785-55d738d87094)


## Notes
Ensure the users.db file is in the same directory as the script.
Passwords must be at least 6 characters long to ensure security.

