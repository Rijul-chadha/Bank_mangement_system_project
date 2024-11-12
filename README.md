# 🏦 Bank Management System

### This Bank Management System project in C++ provides a simple command-line interface for managing bank accounts. It allows users to create, modify, and delete accounts, and to perform deposit and withdrawal operations. The system uses file handling to store account data persistently.

## 🚀 Features

**Create New Account:** Open a new bank account by entering account number, holder name, account type, and initial deposit.

**Deposit Amount:** Deposit a specified amount into an account.

**Withdraw Amount:** Withdraw a specified amount, with a check for sufficient balance.

**Balance Inquiry:** Display balance details for a specific account.

**Display All Accounts:** Show a list of all accounts with details.

**Close Account:** Delete an account from the system.

**Modify Account:** Update details of an existing account.



# 🛠️ Getting Started

### Prerequisites
To compile and run this program, ensure you have a C++ compiler like g++.

### Running the Program

Clone the Repository

git clone https://github.com/your-username/BankManagementSystem.git

cd BankManagementSystem

### Compile the Program

g++ bank_management.cpp -o bank_management

### Run the Executable

./bank_management

# 📁 Program Structure

The main class, account, manages all account-related functions:
Key Methods:

**create_account():** Creates a new account.

**show_account():** Displays details of an account.

**modify():** Modifies account details.

**dep()**: Adds a deposit to the balance.

**draw():** Deducts an amount from the balance.

**report():** Outputs a summary of the account.

**Getter methods:** Access account number, balance, and account type.


# File Management

Data is stored in a binary file account.dat. Each operation updates this file, making the data persistent across sessions.
File Functions:

**write_account():** Saves a new account to account.dat.

**display_sp(int):** Shows details of a specific account.

**modify_account(int):** Updates account information.

**delete_account(int):** Removes an account by using a temporary file.

vdisplay_all():** Lists all accounts.

**deposit_withdraw(int, int):** Handles deposits and withdrawals.

