# Expense-Tracking-Application-using-Python
A simple command-line based Expense Tracking Application developed using Python to help users record, manage, and analyze their daily expenses efficiently.

💰 Expense Tracker (Console-Based Python Application)

A simple console-based Expense Tracker built using Python.
This project allows users to record daily expenses and view spending summaries through a menu-driven interface.

The application is developed using fundamental Python concepts such as loops, conditionals, lists, and dictionaries.

📌 Project Objective

The goal of this project is to:

Practice Python fundamentals

Implement real-world logic using basic programming concepts

Understand how financial data can be stored and processed programmatically

Build a structured menu-driven console application

🚀 Features

➕ Add new expense (Date, Category, Description, Amount)

📋 View all recorded expenses

💰 Calculate total spending

📊 View spending by category

❌ Exit program gracefully

🛠 Concepts Used

while loop – to continuously display the menu

if-elif-else – to handle user choices

list – to store multiple expense records

dictionary – to store expense details

for loop – to calculate totals and display data

input() and print() – for user interaction

📂 Data Structure Used

Each expense is stored as a dictionary:

{
    "date": "05-11-2025",
    "category": "Food",
    "description": "Lunch",
    "amount": 150.0
}


All expense dictionaries are stored inside a list:

expenses = []

▶️ How to Run the Project

Install Python (version 3.x)

Download or clone this repository

Open terminal / command prompt

Run the file:

python expense_tracker.py

📌 Sample Menu
======= MENU =======
1️⃣ Add Expense
2️⃣ View All Expenses
3️⃣ View Total Spending
4️⃣ View Spending by Category
5️⃣ Exit
=====================

📖 Limitations

Data is stored only during runtime (no file/database storage)

No user-defined functions used

Console-based interface only

🎯 Future Improvements

Add file handling for permanent storage

Implement database integration (SQLite/MySQL)

Add graphical interface (Tkinter / Web-based)

Add monthly and yearly reports
