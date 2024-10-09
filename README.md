# Expense-tracker
Expense Tracker
A simple, easy-to-use Python desktop application designed to help you track and manage your daily expenses. The application features a user-friendly interface built with Tkinter and stores expense data in an SQLite database for persistent storage.

Features
Add Expenses: Log expenses with details such as date, name, title, and amount.
View Expenses: Display all logged expenses in a table for easy review.
Total Expenses: Automatically calculate and display the total amount spent.
Persistent Data: Uses SQLite to save expenses across sessions.
Tech Stack
Python: Core application logic.
Tkinter: For building the graphical user interface.
SQLite: To store and manage expense data.
tkcalendar: Date picker widget for selecting dates easily.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/expense-tracker.git
Install the necessary dependencies (e.g., tkcalendar):

bash
Copy code
pip install tkcalendar
Run the application:

bash
Copy code
python expense_tracker.py
Usage
Add Expenses: Enter the date, name, title, and amount of your expense, then click "Submit."
View Expenses: Click "View expenses" to see a list of all recorded expenses along with the total.
Database
All expenses are saved in a local SQLite database (expenseTracker.db). This ensures that your data is available even after closing the application.

License
This project is open-source and available under the MIT License.
