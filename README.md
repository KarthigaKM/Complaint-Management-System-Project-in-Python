# [Project 4: Complaint Management System Project in Python](https://github.com/KarthigaKM/Complaint-Management-System-Project-in-Python)
## Overview:
   * The "Complaint Management System" is a Python-based system that allows users to register, log in, submit complaints, track complaint status, and update complaint details. The project utilizes the MySQL database to store user information and complaint data.
## Key Features:
   * User Registration: Users can register with a unique username and password. User data is stored in the MySQL database.
   * User Login: Registered users can log in using their credentials to access the system.
   * Complaint Submission: Logged-in users can submit multiple complaints, each with a description. The complaints are stored in the database with a default status of "Pending."
   * Complaint Status Tracking: Users can view the status of their submitted complaints, showing the complaint ID, description, and status (e.g., "Pending").
   * Complaint Resolution: Users can update the description of their submitted complaints. The updated descriptions are stored in the database.
## Project Structure:
   * The project is organized into several functions, each handling specific functionalities of the system:
## Database Initialization: 
   * Connects to the MySQL database and creates two tables: "users" to store user information and "complaints" to store complaint data.
## User Registration: 
   * Registers users by accepting a username and password. The user data is stored in the "users" table.
## User Login: 
   * Allows registered users to log in by providing their username and password. The function returns the user ID upon successful login.
## Complaint Submission: 
   * Allows users to submit complaints. The function accepts the user ID and the complaint description and stores the complaint data in the "complaints" table with a default status of "Pending."
## Complaint Status Tracking: 
   * Retrieves all complaints submitted by a specific user and displays their complaint ID, description, and status.
## Complaint Resolution: 
   * Allows users to update the description of their submitted complaints. The updated description is stored in the "complaints" table.
## Main Program: 
   * Handles the overall flow of the Complaint Management System. It includes options for user registration, login, submitting complaints, tracking complaint status, updating complaint status, and logging out.
## Future Enhancement:
   *  Display this in User Interface application like Streamlit
