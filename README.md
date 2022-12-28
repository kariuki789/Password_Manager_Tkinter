# Password_Manager_Tkinter
This is a Python program that uses the tkinter library to create a graphical user interface (GUI) for a password manager. The password manager allows the user to generate a new password, save it along with the associated website and email, and retrieve a saved password for a given website.

The password generator function generate_password() creates a random password by combining letters, symbols, and numbers. It does this by creating three lists: one for letters, one for symbols, and one for numbers. The function then selects a random number of elements from each list and combines them into a single list. The function shuffles the combined list and joins the elements to create the final password, which it then displays in the GUI and copies to the clipboard.

The save() function allows the user to save a website, email, and password combination to a JSON file called "data.json". If the file does not exist, it creates a new file and saves the data. If the file already exists, the function updates the data in the file with the new data.

The find_password() function allows the user to retrieve a password for a given website. It does this by reading the data from the "data.json" file and checking if the website exists in the data. If it does, the function retrieves the associated email and password and displays them in a message box. If the website does not exist, the function displays an error message.

The rest of the code sets up the GUI using the tkinter library. It creates labels, entry fields, and buttons for the user to interact with the password manager.
