# Timetable Filter and Display

## Overview

This Python script processes and filters timetable data from multiple CSV files. It combines data from all CSV files, filters it based on user-specified course codes and departments, and displays the results in an HTML table with random colors assigned to each course code for easy identification.

# Features
- Load Data: Reads and combines timetable data from multiple CSV files located in the /content/ directory.
- Filter Data: Filters data based on user-provided course codes and department codes.
- Visual Display: Displays filtered results in an HTML table with random colors assigned to each course code.
Files
- CSV files containing timetable data (must be uploaded to the /content/ directory in Google Colab).
Installation
- This script is intended to be used in Google Colab. No additional installation is required beyond a Google Colab environment.

## Usage Guide

- Step 1: Upload CSV Files
Ensure your timetable CSV files are uploaded to the /content/ directory in your Google Colab environment.
- Step 2: Load and Run the Script
   - Open a new Google Colab notebook or use an existing one.
   - Download the ipynb file.
- Step 3: Provide Inputs
   - Number of Courses: Enter the number of courses you want to filter.
   - Course Codes: Input each course code one by one as prompted.
   - Number of Departments: Enter the number of departments you want to filter.
   - Department Codes: Input each department code one by one as prompted.
   - The script will filter the timetable data based on your inputs and display the results in an HTML table with randomly assigned colors for each course.

## Notes
Ensure the CSV files are correctly formatted and uploaded to the /content/ directory.
The random colors are generated dynamically and are not persistent between script runs.

![Output](images/your-image.png)
