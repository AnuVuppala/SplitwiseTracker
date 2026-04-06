# 💸 SplitEasy – Group Expense Tracker

A web-based application to track shared expenses and simplify settlements among group members.

## 🚀 Features
- Add and manage group members
- Record expenses with payer and split details
- Automatically calculate balances
- Suggest optimal settlement transactions
- Interactive and responsive UI

## 🧠 How It Works

### 1. Expense Tracking
Each expense stores:
- Description
- Amount
- Payer
- Participants

### 2. Balance Calculation
- The payer is credited the full amount
- Each participant is debited their share

### 3. Settlement Algorithm
A greedy algorithm is used:
- Identify creditors (owed money)
- Identify debtors (owe money)
- Match them to minimize number of transactions

## 🛠️ Tech Stack
- HTML
- CSS
- JavaScript (DOM manipulation)

## ▶️ How to Run
Open `index.html` in a browser

## 📌 Future Improvements
- Persistent storage (LocalStorage / Database)
- Authentication system
- Mobile app version
- Advanced analytics

## 💡 Learning Outcomes
- State management in frontend apps
- DOM manipulation
- Algorithm design (greedy approach)
- Problem-solving and UI design
