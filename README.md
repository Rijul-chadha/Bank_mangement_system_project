# 🏦 Bank Management System

## 📖 Introduction

The **Bank Management System** is a console-based application built using **C++**. It enables users to manage bank accounts efficiently by performing essential banking operations such as account creation, deposits, withdrawals, and account modifications. The system uses file handling to store account data persistently, ensuring that all records are securely saved and accessible between sessions.

---

## ✨ Features

The system offers the following functionalities:

1. **Create New Account** 📝  
   - Add a new account by entering account details such as account number, holder's name, account type, and initial deposit.

2. **Deposit Amount** 💵  
   - Deposit money into an existing account by entering the account number and the amount to be deposited.

3. **Withdraw Amount** 🏧  
   - Withdraw money from an account while ensuring sufficient balance.

4. **Balance Enquiry** 📊  
   - Check the current balance of a specific account by providing the account number.

5. **Account Holder List** 📋  
   - View a complete list of all account holders, including their account numbers, names, account types, and balances.

6. **Close Account** ❌  
   - Delete an account permanently from the database.

7. **Modify Account Details** ✏️  
   - Update account holder details, such as the name, account type, or balance.

8. **Exit** 🚪  
   - Safely exit the application.

---

## 🛠️ How It Works

### Backend Logic

- **File Handling**:  
  All account data is stored in a binary file (`account.dat`) using file handling. This ensures data persistence even after the application is closed.

- **Account Class**:  
  The application uses an `account` class to define the structure of an account, including:
  - Account number
  - Account holder's name
  - Account type (Savings/Current)
  - Balance

- **Functional Modules**:
  - Account creation (`create_account`)
  - Deposit and withdrawal handling (`dep` and `draw`)
  - Record updates (`modify_account`)
  - Record deletion (`delete_account`)
  - Displaying account details (`show_account` and `display_all`)

### Workflow

1. **User Input**:  
   The user selects an option from the main menu to perform an operation.
   
2. **Operation Execution**:  
   Based on the selected option, the program executes the corresponding function (e.g., `write_account` for account creation or `deposit_withdraw` for deposits/withdrawals).

3. **File Updates**:  
   Changes to account details are reflected in the binary file (`account.dat`) using file handling operations such as reading, writing, and updating records.

---

## 🚀 Usage

### Prerequisites

- A C++ compiler (e.g., GCC, MinGW, or Visual Studio).
- Basic understanding of terminal/console operations.

### Steps to Run the Program

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/bank-management-system.git
