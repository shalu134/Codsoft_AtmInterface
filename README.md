# Codsoft_AtmInterface
# ATM Interface – Codsoft Internship Task 3

# Overview

This project is the third task of my Codsoft Java Internship.
It is a console-based ATM interface simulation built in Java. The program allows users to perform basic banking operations such as checking balance, depositing money, withdrawing money, and viewing transaction history.

The goal of this project is to demonstrate the ability to:

Work with conditional statements, loops, and methods in Java.

Simulate real-world applications in a console environment.

Handle user input safely and provide meaningful feedback.

Apply modular programming principles for clean and maintainable code.
# Features

Check balance: Display current account balance.

Deposit money: Allow users to deposit money into their account.

Withdraw money: Allow withdrawals with balance check to prevent overdraft.

Transaction history: Keep a log of deposits and withdrawals for the session.

PIN verification: Simulate a simple security check (optional).

Menu-driven interface: Users can select operations easily via a menu
# Objectives

This task was designed to:

1. Practice Java programming fundamentals in a real-world simulation.


2. Understand console-based user interfaces.


3. Demonstrate ability to track and manipulate data (balance, transactions).


4. Learn to write modular code with methods for each operation.
# Tools & Technologies

Programming language: Java (JDK 11 or later recommended)

IDE / Editor: Eclipse, IntelliJ IDEA, VS Code, or any Java-compatible editor

Standard Libraries: java.util.Scanner for input handling, java.util.ArrayList for transaction history
# How to Run

1️⃣ Clone the Repository

git clone https://github.com/<your-username>/atm-interface.git
cd atm-interface

2️⃣ Compile the Code

javac ATMInterface.java

3️⃣ Run the Program

java ATMInterface
# Example Output

Welcome to the ATM Interface
Enter your PIN: 1234

Select an option:
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Transaction History
5. Exit

Enter your choice: 2
Enter amount to deposit: 5000
Deposit successful. Current Balance: 5000

Enter your choice: 3
Enter amount to withdraw: 2000
Withdrawal successful. Current Balance: 3000

Enter your choice: 4
Transaction History:
Deposit: 5000
Withdrawal: 2000

Enter your choice: 5
Thank you for using the ATM
