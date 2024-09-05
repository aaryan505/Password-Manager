# Password Manager

This is a simple **Password Manager** application built using Python and the Tkinter library for the GUI. The application generates strong random passwords, allows you to save website login details (website, email, and password), and stores them locally in a file. It also copies the generated password to your clipboard automatically for easy use.

## Features
- Generate strong random passwords with letters, numbers, and symbols.
- Save website login details to a local text file (`data.txt`).
- Automatically copy the generated password to the clipboard using the `pyperclip` library.
- Simple and intuitive graphical user interface (GUI).

## Prerequisites
- Python 3.x
- `tkinter` (comes pre-installed with Python)
- `pyperclip` library (Install using: `pip install pyperclip`)

## How to Run the Project
1. Clone or download the repository.
2. Make sure you have the necessary libraries installed (`pyperclip`).
3. Place an image file named `logo.png` in the appropriate path to display the logo (as referenced in the `PhotoImage` section).
4. Run the script using the command:
   ```bash
   python password_manager.py
## How to Use
Open the Password Manager.
Enter the website and email (or username) details.
Click the Generate Password button to create a random, strong password.
Click Add to save the login details (website, email, and password) in the data.txt file.
The generated password will also be copied to your clipboard for easy pasting.
# File Structure
password_manager.py: The main Python file containing the application code.
data.txt: The file where all login details are stored (generated after running the app).
logo.png: The logo displayed on the GUI (should be provided by the user).
## License
This project is licensed under the MIT License - see the LICENSE file for details.
