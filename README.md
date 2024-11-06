# Folder-and-Subfolder-Creator
This script allows you to create folders and subfolders based on data from an Excel file. It reads the folder and subfolder names from the provided Excel file and creates the directories accordingly in a specified root directory.

Features
Reads folder and subfolder names from an Excel file.
Dynamically creates directories and subdirectories based on the data in the Excel file.
User-friendly prompts to provide the root directory and Excel file path.
Cross-platform: works on Windows, Linux, and macOS.
Prerequisites
Before using this script, make sure you have the following:

Python 3.x installed on your machine.

pandas library installed. You can install it using pip:

bash
Copiar código
pip install pandas
Excel file with two columns: "Folder" (folder name) and "Subfolder" (subfolder name).

Setup
Download or Clone the Repository: If you haven't already, clone the repository or download the script file to your local machine.

Prepare Your Excel File: Ensure your Excel file contains two columns: Folder and Subfolder. Here's an example of how your file should look:

Folder	Subfolder
Folder1	Subfolder1
Folder1	Subfolder2
Folder2	Subfolder1
Folder3	Subfolder1
Save the file as .xlsx, and ensure it's accessible from your script.

Run the Script: Execute the script, and it will prompt you to enter the following:

The root directory where the folders will be created.
