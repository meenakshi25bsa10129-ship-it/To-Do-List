To-Do_List
To Do List is a single page web app that lets users manage a simple list of tasks. Users can add and remove tasks from the list. It was coded using a single standard technology named Python.

💡 Overview of the Project
This project is a basic, command-line interface (CLI) application developed in Python. It allows a user to manage a personal list of tasks. The application is designed for simplicity, providing core functionality like adding, viewing, and deleting tasks within an interactive loop.

✨ Features
The application provides the following functionalities through a menu-driven interface:

Add Task (1): Allows the user to input a new task description, which is then added to the list.
View Tasks (2): Displays all current tasks in a numbered list format.
Delete Task (3): Prompts the user to enter the number corresponding to the task they wish to remove from the list.
Exit (4): Closes the application.
💻 Technologies/Tools Used
Category	Technology/Tool	Purpose
Programming Language	Python 3	Core language used to write the application logic.
Data Structure	Python List (tasks)	Used to store and manage the tasks in memory.
Control Flow	while True loop	Creates the continuous, interactive menu system.
Input/Output	input() and print()	Handles user interaction and displays output to the console.
⚙ Steps to Install & Run the Project
Since this is a single-file Python script, the setup is minimal.

1. Prerequisites
You must have Python 3 installed on your system.

2. Installation
Save the Code: Copy the provided Python code and save it into a file named todo.py on your computer.
Open Terminal: Navigate to the directory where you saved todo.py using your command prompt or terminal.
3. Running the Project
Execute the script using the Python interpreter:

bash python todo.py

The application's main menu will now appear in your terminal, and you can begin interacting with it.

🧪 Instructions for Testing
Test the application by running the script and following these steps:

Test Case 1: Add and View Tasks (Options 1 & 2)
Select option 1 (Add Task).
Enter the task "Buy groceries".
Select option 1 again.
Enter the task "Finish report".
Select option 2 (View Tasks).
Expected Result: The output should show:

--- Your Tasks ---

Buy groceries
Finish report
Test Case 2: Delete Task (Option 3)
Ensure you have at least two tasks (as per Test Case 1).
Select option 3 (Delete Task).
When prompted, enter the number 1.
Expected Result: The console prints Task 'Buy groceries' deleted.
Select option 2 (View Tasks).
Expected Result: The list now only shows 1. Finish report.
Test Case 3: Invalid Input and Exit (Options 3 & 4)
Select option 5 (an invalid choice).
Expected Result: The console prints Invalid choice. Please try again.
Select option 3 (Delete Task). When prompted for the number, enter a or 5 (if only one task exists).
Expected Result: The console prints either Invalid input. Please enter a number. or Invalid task number.
Select option 4 (Exit).
Expected Result: The console prints Exiting To-Do List. Goodbye! and the program terminates.

