Pet Grooming Database System

This is a simple database application to manage and track pet grooming records using Python, SQLite, and Tkinter. Below is an overview of its main features.

Features

Data Loading: Loads pet grooming data from a CSV file (pet_grooming_data_final.csv) into an SQLite database (pet_grooming.db).

Record Insertion: Allows users to add new pet grooming records through a form. Validates the data, specifically ensuring only valid pet types (Dog, Cat, Rabbit) are allowed. After submission, the record is saved to the database and appended to the CSV file.

View Records: Displays all stored records in a separate window with scrollable tables, showing all details. If any field is empty, it displays as "nil."

Search Records: Users can search records by Customer ID or Pet Name. Results are displayed in a scrollable table with "nil" shown for any missing data.
Usage

Insert New Record: Click "Insert New Record" to open a form for adding a new pet grooming record.

View Past Records: Click "View Past Records" to see a list of all stored records in a table format.

Search Past Records: Click "Search Past Records" to find specific records by Customer ID or Pet Name.

Requirements

This app uses:

sqlite3 for database management

pandas for data manipulation

tkinter for the graphical user interface
