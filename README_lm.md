# Library Management System 
![image](https://github.com/YashPatel04/Library-Management-System/assets/132531512/1ee4012d-ce77-4ffa-9374-04adaa928a49)

## Overview
This project is a Library Management System (LBMS) implemented in Python. It serves as a comprehensive solution for managing and organizing a library's resources, including books, members, and borrowing records. Leveraging CRUD operations on a MySQL database, it facilitates efficient management of library operations.

## Features
- **Book Management**: Allows users to perform essential operations such as adding, updating, viewing, and removing books from the library's catalog.
- **Member Management**: Facilitates book issuance and return processes, with the ability to link book issues to specific borrower IDs.

## Installation
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Update the MySQL password and database information in `mysql_connector.py` to match your local MySQL setup.
4. Run `main.py` to launch the application.
### Running the code as an exe file 

Note: The exe file that I have committed may not work for you. To run the program as an exe:
- Open the project in an IDE(preferably pyCharm) and make sure you have venv directory containing all the dependencies.
- Install pyinstaller by using the command `pip install pyinstaller`
- Enter the `src` directory in the terminal and execute the command `pyinstaller.exe --onefile --noconsole --paths=Library-Management-System\venv\Lib\site-packages --icon=bit.ico main.py`
- Look for the application named `main` in the dist folder and your exe file is ready.

## Usage
Upon launching the application, users are presented with a user-friendly menu interface that guides them through various operations. Simply follow the on-screen instructions and options to utilize the system effectively.

## Dependencies
This project relies on the following dependencies:
- Python 3: Ensure you have Python 3 installed on your machine.
- Tkinter: Python's de-facto standard GUI (Graphical User Interface) toolkit.
- Pillow: Python Imaging Library (PIL) fork for handling image processing tasks.
- image tk: Tkinter extension for displaying images.
- MySQL: Ensure you have MySQL installed and running, as the project utilizes a MySQL database for data storage.

## Contributing
Contributions via pull requests are always appreciated. Feel free to contribute enhancements, bug fixes, or additional features to improve the project.

