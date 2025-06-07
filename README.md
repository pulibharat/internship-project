# internship-project
# 💰 Smart Expense Tracker (Python CLI)

Track your daily expenses with smart AI-like categorization!  
A simple and intelligent command-line Python app that saves and summarizes your expenses, day by day 💸

---

## 🚀 Features

- 📅 Track daily expenses with date, amount, and description
- 🧠 Automatically guesses the **category** using smart keyword matching
- 💾 Saves all data in a `CSV` file (`smart_expenses.csv`)
- 📊 Daily summary with total spend, number of entries, and smart comments (e.g. "Light day 💡", "Heavy spender alert 🚨")

---

## 🔧 How It Works

1. **Add Expense**  
   - Enter a short description (e.g., "Paid Swiggy", "Movie tickets")
   - Amount and date
   - The program guesses category (like Food, Transport, etc.)

2. **View All Expenses**  
   - See all saved expenses with category and amount

3. **Daily Summary**  
   - Summarizes how much you spent each day
   - Adds a smart comment based on your spending level

---

## 🛠️ Technologies Used

- Python 3
- CSV File Handling
- `collections.defaultdict` for grouping
- Simple logic-based AI for category detection

---

## 📁 File Structure

