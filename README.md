# 💰 Expense Tracker (Python)

A simple command-line Expense Tracker built with Python that allows users to enter expenses one by one, calculates the running total, and displays the final total when the user exits.

---

## 📌 Features

- ➕ Add multiple expense amounts
- 📊 Displays running total after each entry
- ✅ Handles invalid input using exception handling
- 🚪 Exit anytime by typing `quit`
- 💵 Displays the final expense total

---

## 🛠️ Technologies Used

- Python 3
- Functions
- Loops (`while`)
- Exception Handling (`try-except`)
- User Input
- Variables

---

## 📂 Project Structure

```
expense_tracker.py
README.md
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/expense-tracker.git
```

2. Navigate to the project folder

```bash
cd expense-tracker
```

3. Run the program

```bash
python expense_tracker.py
```

---

## 💻 Sample Output

```text
--- Expense Tracker ---
Type 'quit' to exit and see your final total.

Enter expense amounts one by one.

Enter expense amount: 400
Added! Current running total: $ 400.0

Enter expense amount: 300
Added! Current running total: $ 700.0

Enter expense amount: 500
Added! Current running total: $ 1200.0

Enter expense amount: quit

==============================
FINAL TOTAL: $ 1200.0
==============================
```

---

## 📜 Code Highlights

- Uses a global variable to store the total expense.
- Uses a `while` loop for continuous expense entry.
- Uses `try-except` to prevent crashes from invalid inputs.
- Displays the final total after exiting.

---

## 🚀 Future Improvements

- Save expenses to a file
- Add expense categories
- Show expense history
- Monthly expense report
- GUI version using Tkinter
- Data visualization with Matplotlib

---

## 👨‍💻 Author

**Krish Kumar**

If you found this project helpful, feel free to ⭐ the repository.
