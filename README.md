# Python_Projects
Project Summary: Command-Line Attendance Tracker

1. Project Objective

This project is a simple command-line application based on Python programming, designed to record and manage attendance (presence) in schools, colleges, or small workplaces. Its main objective is to automate the time-consuming process of manual attendance recording and to practice the fundamental concepts of Python.

2. Key Features

The application provides the following key functionalities:

Data Collection: It accepts student names and check-in times as input from the user and efficiently stores this data in a Python Dictionary.

Robust Data Validation:

Rejects any empty name (Empty Name) or missing timestamp (Missing Time) entry.

Checks to prevent duplicate entries, ensuring data accuracy.

Formatted Summary Display: Displays the recorded attendance on the console in a clean, aligned tabular format using f-strings and tabs (\t).

Absentee Calculation (Optional): Calculates the number of Total Present and Total Absent students based on the Total Class Strength and includes this data in the report.

Report Saving (Bonus): Provides an option to save the report to a text file named attendance_log.txt, which also includes the current date and time (timestamp) of the report generation using the datetime module.

3. Python Concepts Used

The following fundamental Python programming concepts have been successfully implemented in this project:

Data Structures: Usage of Lists and Dictionaries to store and manage attendance records.

Control Flow: Usage of for and while loops for handling multiple entries and data validation.

Conditional Statements: Usage of if-elif-else for validating input data and preventing duplicate entries.

File Handling: Usage of open() and write() functions to permanently save the report to a .txt file.

Module Usage: Usage of the datetime module for adding timestamps to the report.