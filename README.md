# Medicine-system
Python Mini Project – Medicine System. Hemachandan L_1BG24BA057
# Description
The Medicine Reminder System is a menu-driven, console-based Python application designed to help users manage and track their daily medicines. It is especially useful for elderly people and patients who may forget to take medicines on time. The system allows users to add medicines, view schedules, mark medicines as taken, and track pending doses in an organized and simple manner.

This project is developed as part of the Python Mini Project assignment and demonstrates the practical use of core Python concepts taught in class.


# Features
- Add new medicines with ID, name, dosage, and timing
- View all medicines with complete details
- Search medicines by ID or name (case-insensitive)
- Mark medicines as taken with automatic date and time
- View today’s medicine schedule with taken/pending status
- Delete medicines that are no longer required
- Save and load data automatically using an Excel file
- Handles invalid user input using exception handling


# Concepts Used

# Data Structures
- *List* to store multiple medicine records  
- *Dictionary* to store individual medicine details  
- *List of dictionaries* for organized data management  

# Control Flow
- while loop for continuous menu execution  
- for loops for iterating through records  
- if / elif / else statements for menu selection and validation  

# Functions
User-defined functions are used to separate logic, such as:
- Adding medicines
- Searching medicines
- Viewing schedules
- Marking medicines as taken
- Saving and loading data

# Methods Used
- *List methods*: append(), remove()  
- *Dictionary methods*: get(), update()  
- *String methods*: upper(), lower(), split(), ljust()  

# Exception Handling
- try / except blocks are used to handle invalid input and file-related errors gracefully

# Instructions to Run the Program

# Requirements
- Python 3.6 or higher
- Jupyter Notebook
- Required libraries: pandas, openpyxl

# Installation
bash
pip install pandas openpyxl


### Steps to Run
1. Download the following files:
   - medicine_reminder.ipynb
   - medicine.xlsx
2. Place both files in the same folder
3. Open Jupyter Notebook:
   bash
   jupyter notebook
   
4. Open medicine_reminder.ipynb
5. Run all cells or the main program cell
6. Follow the on-screen menu to use the application


# Input Guidelines

# Adding a Medicine
- *Medicine ID*: Must be unique (e.g., MED001, MED002)
- *Medicine Name*: Any valid medicine name
- *Dosage*: Include units (e.g., 500mg, 10ml, 2 tablets)
- *Time of Day*: Morning / Afternoon / Evening / Night
- *Time*: 12-hour format with AM/PM (e.g., 08:00 AM)

# Menu Navigation
- Enter numbers corresponding to menu options
- Invalid input will display an error message
- Always choose *Save and Exit* to store data properly

# File Handling Details
- Data is stored in an Excel file named *medicine.xlsx*
- The file is loaded automatically when the program starts
- All changes are saved back to the Excel file before exiting
- If the file does not exist, the program starts with empty data and creates the file on save

# Author Information
Name: L Hemachandan  
USN: 1BG24BA057  
Course: Python Programming  
Project: Python Mini Project – Medicine Reminder System  
Domain: Healthcare – Medicine Tracking
