# 💰 Smart Expense Tracker

A Python-based personal finance management application that helps users track income, manage expenses, plan monthly budgets, analyze spending patterns, and generate financial reports.

Built using **Python, Gradio, and JSON**, this project is divided into two modules: Expense & Income Management and Budget Planning & Financial Insights.

---

## 📌 Project Overview

The Smart Expense Tracker provides an interactive interface for managing personal finances efficiently.

It helps users understand their spending habits, monitor their available balance, allocate monthly income, and make better financial decisions.

### Main Modules

**Module 1: Expense & Income Management**
- Add income and expense transactions.
- Edit and delete existing transactions.
- View transaction history.
- Filter transactions by date.
- Calculate total income, expenses, and available balance.

**Module 2: Budget Planning & Financial Insights**
- Create monthly budget plans.
- Allocate salary across different categories.
- Analyze monthly spending.
- Generate financial tips.
- Analyze expenses by category.
- Generate downloadable TXT reports.

---

## ✨ Features

### 1. Dashboard
- View total income.
- View total expenses.
- Calculate available balance.
- Display transaction history.

### 2. Transaction Management
- Add income and expenses.
- Assign categories and descriptions.
- Generate unique transaction IDs.
- Edit transaction details.
- Delete transactions.
- Validate transaction inputs.

### 3. Transaction Filtering
Filter transactions using:
- All Transactions
- Today
- Last 7 Days
- This Month
- Last 30 Days
- Custom Date Range

### 4. Budget Planning
- Enter monthly salary.
- Allocate income using percentages.
- Set allocations for rent, food, travel, savings, emergency funds, shopping, entertainment, and other expenses.
- Validate that total allocation equals 100%.
- Calculate category-wise allocated amounts.

### 5. Budget Analysis
- Compare allocated budgets with actual expenses.
- Calculate remaining amounts.
- Identify categories exceeding their budgets.
- Display current-month financial summaries.

### 6. Financial Tips Generator
- Generate financial tips.
- Get suggestions related to saving, budgeting, shopping, food, investment, and emergency funds.
- Calculate remaining income.
- Receive spending and savings suggestions based on entered values.

### 7. Category Analysis
- Calculate total expenses by category.
- Display categories in descending order of spending.

### 8. Report Generation
- Generate financial summary reports.
- Include total income, expenses, and available balance.
- Include transaction history.
- Download reports in TXT format.

---

## 🎯 Problem Statement

Managing personal finances manually can make it difficult to track income, monitor expenses, and maintain a monthly budget.

People may struggle to identify spending patterns, control unnecessary expenses, and understand their financial position.

**Solution:** Smart Expense Tracker provides a centralized application to record transactions, organize expenses, plan budgets, analyze spending, and generate financial reports.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Gradio | Interactive user interface |
| JSON | Data storage and persistence |
| OS | File and directory management |
| UUID | Unique transaction ID generation |
| Datetime | Date handling and filtering |
| Random | Randomized financial tips |

---

## ⚙️ How It Works

### Module 1: Expense & Income Management

1. The user enters transaction details such as type, amount, category, description, and date.
2. The application validates the entered information.
3. A unique transaction ID is generated.
4. Transaction details are saved in `transactions.json`.
5. The dashboard calculates total income, total expenses, and available balance.
6. Users can filter, edit, or delete transactions.

### Module 2: Budget Planning & Financial Insights

1. The user enters their monthly salary.
2. The user allocates salary percentages across different categories.
3. The application validates the allocation percentages.
4. The budget plan is saved in `budget.json`.
5. The application compares the planned budget with actual monthly expenses.
6. Financial tips are generated based on the entered salary and expenses.
7. Users can analyze category-wise expenses and download TXT reports.

---

## 📂 Project Structure

```text
SMART-EXPENSE-TRACKER/
│
├── SMART EXPENSE TRACKER.ipynb
│
├── data/
│   ├── transactions.json
│   └── budget.json
│
├── reports/
│   └── expense_report.txt
│
└── README.md
```

**Note:** The `data` and `reports` directories and their files are created automatically when the application runs. The notebook contains both application modules.

---

## 🚀 Installation & Execution

### Prerequisites

- Python 3.9 or above
- Jupyter Notebook or JupyterLab
- Internet connection for installing Gradio

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/smart-expense-tracker.git
```

### Step 2: Navigate to the Project Directory

```bash
cd smart-expense-tracker
```

### Step 3: Install Dependencies

```bash
pip install gradio
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Application

1. Open `SMART EXPENSE TRACKER.ipynb`.
2. Execute the notebook cells sequentially.
3. Launch Module 1 for expense and income management.
4. Launch Module 2 for budget planning and financial insights.

**Important:** Both modules use the same transaction JSON file. Run the notebook cells in sequence so the shared classes, objects, and data files are initialized correctly.

---

## 💾 Data Storage

The application uses JSON files for local data persistence.

**transactions.json**

Stores:
- Transaction ID
- Transaction type
- Amount
- Category
- Description
- Date

**budget.json**

Stores:
- Monthly salary
- Category-wise budget allocations

**expense_report.txt**

Contains:
- Report generation date
- Total income
- Total expenses
- Available balance
- Transaction history

---

## 🌍 Real-World Applications

- **Personal Finance:** Manage daily income and expenses.
- **Student Budgeting:** Track allowances and spending.
- **Household Management:** Organize monthly household expenses.
- **Freelancers:** Maintain basic income and expense records.
- **Small Businesses:** Monitor basic financial transactions.
- **Financial Planning:** Analyze spending habits and plan savings.

---

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Python programming.
- Object-Oriented Programming (OOP).
- Building interactive applications using Gradio.
- JSON file handling and data persistence.
- CRUD operations (Create, Read, Update, Delete).
- Input validation and exception handling.
- Date-based filtering.
- Budget allocation and financial calculations.
- Generating downloadable reports.
- Developing modular applications.

---

## 🔮 Future Enhancements

- Add database integration using SQLite or MySQL.
- Implement user authentication.
- Add interactive charts and graphical dashboards.
- Introduce automatic recurring transactions.
- Add CSV and Excel export functionality.
- Implement advanced spending analytics.
- Add cloud-based data synchronization.
- Develop a mobile-friendly interface.

---

## 👨‍💻 Project Information

**Project Name:** Smart Expense Tracker

**Domain:** Python Development | Personal Finance Management

**Programming Language:** Python

**Interface Framework:** Gradio

**Storage:** JSON

**Project Type:** Personal Finance Management Application

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub!

**Developed as a practical project to strengthen Python programming and application development skills.**

