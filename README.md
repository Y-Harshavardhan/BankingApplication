# Simple Banking Application

A Java-based console application for managing bank accounts. This program allows users to create accounts, deposit money, withdraw money, and check account balances.

## Features
- **Create Account**: Create a new bank account with an account number, account holder name, and initial balance.
- **Deposit Money**: Deposit funds into an existing account.
- **Withdraw Money**: Withdraw funds from an existing account (if sufficient balance is available).
- **Check Balance**: View the current balance of an account.
- **Console-Based Interface**: Easy-to-use menu-driven interface for managing accounts.

## How to Run the Program
1. **Compile the Java Code**:
   Open a terminal in the project directory and run:
   ```bash
   javac BankingApplication.java
Example Usage
Create an Account:
Choose an option: 1
Enter account number: 12345
Enter account holder name: John Doe
Enter initial balance: 1000
Account created successfully.
Deposit Money:
Choose an option: 2
Enter account number: 12345
Enter amount to deposit: 500
Deposit successful. New balance: 1500.0
Withdraw Money:
Choose an option: 3
Enter account number: 12345
Enter amount to withdraw: 300
Withdrawal successful. New balance: 1200.0
Check Balance:
Choose an option: 4
Enter account number: 12345
Account Balance: 1200.0
