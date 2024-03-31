# Parking Management System

This Python application is a parking management system that allows users to manage parking reservations and payments. It's built using Tkinter for the GUI, MySQL for database management, and ReportLab for PDF generation.

## Features:
- **Multi-step Form**: Utilizes a multi-step form structure for entering parking details and making payments.
- **Database Integration**: Interacts with a MySQL database to store parking data and customer information.
- **PDF Generation**: Generates a PDF receipt summarizing the parking reservation details.

## Requirements:
- Python 3.x
- Tkinter
- MySQL Connector
- ReportLab

## Installation:
1. Clone the repository:

    ```
    git clone https://github.com/<username>/parking-management-system.git
    ```

2. Install the required dependencies:

    ```
    pip install mysql-connector-python
    pip install reportlab
    ```

## Usage:
1. Ensure that MySQL server is running on your system.

2. Run the application:

    ```
    python parking_management_system.py
    ```

3. Follow the instructions on the GUI to enter parking details, make payments, and generate receipts.
To accompany your code, here's a sample README file:

---

# Login System with Python and MySQL

This is a simple login system implemented in Python using the Tkinter library for the GUI and MySQL for database management. The system allows users to log in based on their username and password credentials. Depending on the user's role (admin or customer), they are directed to different pages with distinct functionalities.

## Features

- **Login Page**: Users can log in with their username and password. Invalid credentials trigger an error message.
- **New User Registration**: New users can register with a username, password, and role (admin or customer).
- **Admin Page**: Admin users have access to administrative tasks like viewing tables and updating the database.
- **Customer Page**: Customer users have access to functionalities specific to regular users.

## Requirements

- Python 3.x
- Tkinter library (usually comes pre-installed with Python)
- MySQL database

## Installation and Setup

1. **Clone the Repository:**
   ```
   git clone https://github.com/your_username/login-system.git
   ```

2. **Install Required Packages:**
   ```
   pip install mysql-connector-python
   ```

3. **Database Setup:**
   - Create a MySQL database named `logi`.
   - Import the `database.sql` file provided in the repository to create the required tables.
   - Update the database connection details (host, username, password) in the code if necessary.

4. **Run the Application:**
   ```
   python login_system.py
   ```

## Usage

1. Launch the application by running `login_system.py`.
2. Log in with existing credentials or register as a new user.
3. Based on the user role, access the admin or customer functionalities.
4. Perform actions like viewing tables, updating data, etc., as per the user's role.


## Structure:
- `parking_management_system.py`: Main application script containing the parking management system logic.
- `assets/`: Directory containing image assets used in the GUI.
- `README.md`: Readme file providing information about the parking management system.


## Contributing:
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
