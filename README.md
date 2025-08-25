Daily Expense Tracker 🧾💰

A complete personal finance management application built in Python.

Overview

The Daily Expense Tracker is a Python-based desktop application that helps users manage their daily expenses efficiently. It combines Tkinter for GUI, CSV for data storage, and Excel export capabilities to provide a full-featured personal finance solution.

Features

Add, View, and Delete Expenses: Record expenses with amount, category, date, and description.

Dynamic Totals: Track total expenses, remaining balance (based on income), daily totals, and monthly totals automatically.

Expense Statistics: Generate daily and monthly reports showing breakdown by category with percentage calculations.

Persistent Data Storage: Expenses and income are stored in CSV files (depenses.csv & revenu.csv) ensuring data is saved across sessions.

Excel Export: Export all expenses into a well-formatted Excel file with bold headers, aligned columns, and auto-adjusted widths for clarity.

Responsive and Interactive UI: Treeview columns resize with window changes; scrollbars integrate seamlessly with tables.

Input Validation & Error Handling: Ensures all entries are valid and unique; displays clear error messages when needed.

Interactive Date Selection: Uses tkcalendar's DateEntry for convenient date picking.

Libraries & Tools

Tkinter & ttk: GUI components like frames, labels, entries, buttons, Treeview tables.

tkcalendar: Interactive date selection widget.

uuid: Unique identifiers for each expense entry.

csv & os: Persistent storage and file management.

openpyxl: Generate and style Excel reports.

datetime: Date handling and calculations for totals/statistics.

messagebox: Informative error and success pop-ups.

Combobox: Selection for categories, months, and years.

Technical Details

Expense Objects: Each expense has attributes: amount, category, date, ID, and description.

ExpenseManager Class: Handles adding, removing, and calculating totals with data integrity checks.

Treeview Table: Scrollable, resizable table for easy viewing and selection.

Statistics Pop-ups: Show daily and monthly summaries with category-wise breakdown.

Excel Export: Automatically formats spreadsheet with bold headers, centered text, right-aligned amounts, and auto-width columns.

Benefits

This application provides a user-friendly tool for personal finance management, enabling users to:

Track spending habits daily and monthly.

Analyze categories where most money is spent.

Keep organized records for printing or personal use.

Learn from visual reports and Excel exports to plan budgets better.

Built with Python, Tkinter, CSV, tkcalendar, and openpyxl.
A complete solution combining GUI development, data management, and reporting tools in one easy-to-use desktop application.
