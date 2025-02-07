# Simple Password Generator

This is a **simple password generator** created using **Batch scripting**. The program allows you to easily generate strong passwords, save them in a custom folder, and even store the script for future use. 

The script prompts the user for a password length, generates a password containing **uppercase**, **lowercase**, **digits**, and **special characters**, and saves the generated password in a folder of the user’s choice. The folder is created within the `GeneratedPasswords` directory, which is also created if it doesn't already exist.

## Features:
- **User-defined folder name**: Let users specify a name for the folder where the password and script will be saved.
- **Strong password generation**: Random passwords with uppercase, lowercase, digits, and special characters.
- **Persistence**: The password and script are saved in the newly created folder for easy access.
  
## Usage:
1. Clone or download the repository.
2. Run the `.bat` file by double-clicking it.
3. Enter the desired password length when prompted.
4. Enter a custom folder name when asked. The folder will be created inside the `GeneratedPasswords` directory.
5. The password will be saved in a `.txt` file, and the batch script will be copied to the folder as well.

## Example Folder Structure:
