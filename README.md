Personal Finance Manager

This is a Python-based personal finance manager that tracks your income and expenses by recording transactions into a CSV file. It allows you to add new transactions and view transaction summaries within a specified date range.

Features
    1.Add new transactions (date, amount, category, description)
    2.View transaction history and summaries (income, expenses, net savings) for a given date range
    3.CSV storage for easy data management

Prerequisites
Ensure you have the following installed:

    Python 3.x
    Pandas library
    CSV module (default Python library)
    pip install pandas

Project Structure

    ├── finance_data.csv         # CSV file where the data is stored
    ├── main.py                  # Main file to run the finance manager
    ├── data_entry.py            # Handles user inputs for date, amount, category, description
    └── README.md                # Project documentation

How to Run
    1. Clone the repository:
        git clone https://github.com/Ankit0899/finance_project.git
        cd finance_project
        python main.py

Usage
1. Add a new transaction:
    1. Enter the date, amount, category (Income/Expense), and description of the transaction.
    2. The transaction will be added to finance_data.csv.

2. View transactions within a date range:
    1. Enter the start and end dates, and the script will display all transactions within that range.
    2. It will also show the total income, total expenses, and net savings.

Exit:
    Choose option 3 to exit the application.