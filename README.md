**Growth Mindset Challenge** - **Developed By Faria Mustaqim**

Data Sweeper - Convert Excel to CSV & Vice Versa

Introduction:

Data Sweeper is a powerful tool that allows users to effortlessly convert Excel files (.xlsx) to CSV format and vice versa. The application provides additional data cleaning features, enabling users to handle missing values, remove duplicates, and filter data before conversion.

Key Features Implemented

✅ File Upload & Preview: Users can upload files and preview their data before processing.
✅ Data Cleaning Options: Handle missing values, drop duplicates, and filter data.
✅ Select Columns for Conversion: Choose specific columns for conversion.
✅ File Conversion Options: Convert uploaded files into CSV or Excel formats.
✅ Download Converted Files: Download the cleaned and converted file in the desired format.

Installation & Setup:

**Prerequisites**

Ensure you have the following installed:

Python 3.x
pip (Python Package Installer)
pandas and openpyxl (for file handling)

Install Required Dependencies:

Run the following command to install necessary libraries:

pip install pandas openpyxl

Usage:

Running the Application

Use the following command to run the script:

python file_name.py

Converting Excel to CSV:

Upload an Excel file (.xlsx).

Select the necessary cleaning options (if required).

Click Convert to generate a CSV file.

Download the converted file.

Converting CSV to Excel

Upload a CSV file (.csv).

Apply any necessary data filters.

Click Convert to generate an Excel file.

Download the converted file.

Python Code Example:

Here’s a simple example of converting an Excel file to CSV using pandas:

import pandas as pd

def convert_excel_to_csv(input_file, output_file):
    df = pd.read_excel(input_file)
    df.to_csv(output_file, index=False)

# Example usage
convert_excel_to_csv('input.xlsx', 'output.csv')

Supported File Formats

Excel: .xlsx, .xls

CSV: .csv

Best Practices & Recommendations:

Ensure the file is formatted correctly before uploading.

Use the data cleaning options to enhance output accuracy.

Save your original data before performing conversions.

Author:

📌 By: Faria Mustaqim

