💰 Daily Expense Tracker

A command-line Expense Tracker application built with Python that allows users to record, view, analyze, and delete their daily expenses.

The project uses Object-Oriented Programming (OOP) and stores expense data locally in a JSON file, making it a simple and practical project for learning Python application development and data persistence.

---

✨ Features

- ➕ Add new expenses
- 📋 View all recorded expenses
- 📅 View expenses by a specific date
- 📊 Generate monthly expense summaries
- 🗂️ Analyze expenses by category
- 💵 Calculate total expenses
- 📆 View today's expenses
- 🗑️ Delete expenses using their ID
- 💾 Automatically save data to a JSON file
- ⚠️ Basic input validation and error handling
- 🕒 Automatically record the date and time of each expense

---

🛠️ Technologies Used

- Python 3
- JSON — for storing expense data
- OS — for checking file existence
- datetime — for recording and processing dates and times
- time — for simple processing animations
- Object-Oriented Programming (OOP)

---

📂 Project Structure
```
daily-expense-tracker/
│
├── expense_tracker.py
├── expence.jyson
└── README.md
```
«The JSON data file is created automatically when the program runs.»

---

🚀 Getting Started

1. Clone the repository

git clone https://github.com/umeabia09-cmyk/Daily-Expense-Tracker.git

2. Navigate to the project directory

cd daily-expense-tracker

3. Run the program

python expense_tracker.py

---

📋 Main Menu

When the application starts, it provides the following options:

DAILY EXPENSE TRACKER

1. Add Expenses
2. View All Expenses
3. Monthly Summary
4. Category Summary
5. View Expenses by Date
6. View Today's Expenses
7. Delete Expenses
8. Exit

---

💡 How It Works

Each expense is stored with information such as:

- Expense ID
- Date
- Time
- Amount
- Category
- Description

Example data structure:
```
{
    "ID": 1,
    "Date": "06-09-2026",
    "Time": "10-30-15",
    "Amount": 500.0,
    "Catagory": "Food",
    "Discription": "Lunch"
}
```
The application stores these records locally in JSON format so that the data remains available after the program is closed.

---

📊 Expense Analysis

The application can generate useful summaries, including:

Monthly Summary

Displays:

- Total expenses for the month
- Number of transactions
- Daily spending breakdown

Category Summary

Displays:

- Total spending per category
- Percentage of total expenses
- Categories sorted by spending amount

This makes the project more than a basic CRUD application and demonstrates basic data analysis using Python.

---

🧠 Concepts Demonstrated

This project was created to practice several important Python concepts:

- Classes and objects
- Constructors
- Methods
- Encapsulation
- Lists and dictionaries
- JSON serialization/deserialization
- File handling
- Exception handling
- Input validation
- List comprehensions
- Sorting and aggregation
- Date and time handling
- Loops and conditional statements
- Command-line interfaces

---

🔮 Future Improvements

Possible improvements for future versions include:

- [ ] Add a graphical user interface (GUI)
- [ ] Add charts and spending visualizations
- [ ] Add an edit/update expense feature
- [ ] Improve expense ID management after deletion
- [ ] Add budget tracking
- [ ] Add income tracking
- [ ] Export reports to CSV
- [ ] Add password-protected user accounts
- [ ] Improve date-format consistency
- [ ] Add automated tests
- [ ] Replace JSON storage with a database such as SQLite

---

🎯 Learning Purpose

This project was developed as a hands-on Python project to strengthen understanding of Object-Oriented Programming, file handling, JSON data storage, input validation, and basic data analysis.

It represents my progress in building practical software rather than only writing individual programming exercises.

---


Feel free to ⭐ the repository and explore the code!
