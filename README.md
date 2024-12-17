Daily Expenses Tracker

Overview

The Daily Expenses Tracker is a Python-based web application built with Streamlit. It helps users track, manage, and visualize their daily expenses. The app allows users to add expenses, delete them, calculate daily totals, and visualize expense data. It also supports file operations like loading and saving expenses to CSV files.

Features

Add Expenses: Enter details such as date, category, amount, and description.

Delete Expenses: Remove specific entries by providing the index.

File Operations:

Load expenses from a CSV file.
Save expenses to a CSV file.

Visualization: Visualize expenses by category using bar charts.

Daily Totals: Calculate and display total expenses for each day.

Action History: View a log of actions performed during the session.

Requirements

Python Libraries:
streamlit
pandas
matplotlib
seaborn

Install the required libraries using:
pip install streamlit pandas matplotlib seaborn

How to Run the Application

Clone the repository:
git clone https://github.com/impratishtha/Daily-Expenses-Tracker-

Navigate to the project directory:
cd Daily_Expenses-Tracker-

Run the application:
streamlit run Daily_expenses.py

Open the URL displayed in the terminal (usually http://localhost:8501) in your web browser.
Project Structure

Daily_Expenses-Tracker-
├── Daily_expenses.py    # Main application file
├── requirements.txt     # Dependencies (optional)
└── README.md            # Project documentation

How to Use

Add Expenses: Use the sidebar form to add new expense entries.
View Expenses: The main section displays all added expenses in a table.
Delete Expenses: Enter the index of an expense to delete it.
Visualize Data: Click on the "Visualize Expenses" button to generate a bar chart of expenses by category.
Daily Totals: Calculate and view daily expense totals.

File Operations:

Upload a CSV file to load expenses.
Save expenses to a CSV file for later use.

