# Expense Tracker

## Project Description
This project is a simple Expense Tracker built using Python and Object-Oriented Programming (OOP) principles. It consists of two classes:

- **Expense**: Represents an individual financial expense with attributes such as ID, title, amount, created timestamp, and updated timestamp.
- **ExpenseDB**: Manages a collection of expenses, providing functionalities to add, remove, update, and retrieve expenses.

## Features
- Create new expenses with unique IDs.
- Update expense details (title or amount).
- Remove an expense by its ID.
- Retrieve an expense by ID or title.
- View all expenses in dictionary format.

## Installation
To use this project, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/delightez/Expense-Tracker
cd expense-tracker
```

2. **Set up a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. **Install dependencies** (if any are required in the future)
```bash
pip install -r requirements.txt  # No external dependencies required for now
```

## How to Run the Code
1. Open a Python terminal or create a script.
2. Import the classes from the project:
```python
from expense_tracker import Expense, ExpenseDB
```
3. Create and manage expenses:
```python
# Create an expense
grocery = Expense("Groceries", 5000.0)

# Create a database instance
db = ExpenseDB()

db.add_expense(grocery)

db.to_dict()  # View all expenses
```

## Contributing
Feel free to fork this repository and submit pull requests with improvements!

## License
This project is open-source and free to use under the MIT License.

