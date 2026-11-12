# Excel-Data-Cleaning-Automation
Desktop app built with Python to clean messy Excel files in one click: remove duplicates, blank rows, extra spaces and convert text to Title Case.

## Demo
<img width="1599" height="899" alt="WhatsApp Image 2026-11-12 at 1 32 01 PM" src="https://github.com/user-attachments/assets/75fd7433-9f11-4598-a3d6-c30339f7ec44" />



## Why I Built This

Data cleaning takes up a large part of an analyst's time. Removing duplicates, deleting blank rows and fixing spacing and text casing by hand is slow and error-prone. This tool automates those repetitive steps through an easy-to-use interface.

## Features

- Select any Excel file using a file browser
- Choose only the cleaning options you need:
  - Remove duplicate rows
  - Remove blank rows
  - Remove leading and trailing spaces (text columns only)
  - Convert text columns to Title Case
- Select the output folder for the cleaned file
- Reset Paths button to clear the selected file and folder
- Reset Checkboxes button to clear all selected options
- One-click cleaning with the Clean Data button

## Tech Stack

- Python
- Tkinter (GUI)
- pandas (data processing)
- openpyxl (Excel read/write)

## How to Run

1. Clone the repository

   git clone https://github.com/YOUR-USERNAME/excel-data-cleaning-automation.git
   cd excel-data-cleaning-automation

2. Install the required libraries

   pip install -r requirements.txt

3. Run the application

   python your_file_name.py

## How to Use

1. Click Browse next to Input Excel File and select your file.
2. Tick the cleaning options you want.
3. Click Browse next to Output Folder and choose where to save the result.
4. Click Clean Data.
5. Open the output folder to find your cleaned file.

## Project Structure

    excel-data-cleaning-automation/
    |-- your_file_name.py
    |-- requirements.txt
    |-- demo.mp4
    |-- README.md

## Future Improvements

- Support for CSV files
- Handle missing values (fill or remove)
- Preview data before and after cleaning
- Cleaning report showing how many rows were changed
- Package as a standalone .exe file

## Author

**Neha Gupta**
BCA Graduate | Aspiring Data Analyst
LinkedIn: https://www.linkedin.com/in/neha-gupta-483257379
