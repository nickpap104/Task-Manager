# Task-Manager Description
This code is a task management system that allows users to register, log in, add tasks, view tasks, generate reports, and display statistics. It utilizes text files to store user data and task information.

The program begins by importing necessary libraries and defining constants. It checks for the existence of the "tasks.txt" file and creates it if it doesn't exist. Then, it reads task data from "tasks.txt" and processes it into a list of dictionaries representing tasks.

The login section prompts users to enter their credentials, checks them against data stored in the "user.txt" file, and allows access upon successful authentication.

Once logged in, users can choose from various options:

    Register a new user
    Add a task, specifying details such as username, title, description, and due date
    View all tasks or view tasks assigned to the current user
    Generate reports: user overview or task overview
    Display statistics, including the total number of users, tasks, completed tasks, uncompleted tasks, and overdue tasks

The code includes error handling and ensures proper formatting and data validation throughout the program.
