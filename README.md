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

## Structure:
- `parking_management_system.py`: Main application script containing the parking management system logic.
- `assets/`: Directory containing image assets used in the GUI.
- `README.md`: Readme file providing information about the parking management system.

## Contributing:
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
