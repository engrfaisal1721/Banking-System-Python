# Bank Management System

This repository contains a simple **Bank Management System** implemented in Python using Object-Oriented Programming (OOP) concepts.

The project demonstrates the creation and management of bank accounts with two main classes: **BankAccount** and **Bank**.

---

## 🏦 Classes

### 1. BankAccount
Represents a single bank account.  

**Features:**
- Create an account with account number, holder name, and optional initial balance.
- Deposit money.
- Withdraw money (with balance check).
- Check current balance.

**Example Usage:**
```python
account = BankAccount(101, "Faisal Rehman")
account.Deposite(500)
account.Withdraw(200)
account.GetBalance()
```

## 2. Bank
Manages multiple bank accounts.

**Features:**
- Create new bank accounts.
- Search for an account by account number.
- Deposit money into any account.
- Withdraw money from any account.
- Check balance of any account.

**Example Usage:**
```python
bank = Bank()
bank.Create_Account(101, "Faisal Rehman")
bank.deposite(101, 1000)
bank.withdraw(101, 300)
bank.get_balance(101)
```