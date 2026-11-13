# Stock-Trading-Platform
# Stock Trading Platform – Java

## 📌 Project Overview

The Stock Trading Platform is a console-based Java application that simulates a basic stock market trading environment.

It allows users to view available stocks, buy and sell shares, manage their portfolio, and track their available balance.

## 🎯 Objectives

- To simulate a basic stock trading environment.
- To display stock names and prices.
- To perform buying and selling operations.
- To manage user portfolios.
- To calculate and track available balance.

## ✨ Features

- Display available stocks and their prices.
- Buy stocks by selecting stock quantity.
- Sell previously purchased stocks.
- Track portfolio holdings.
- Display available account balance.
- Prevent purchases with insufficient balance.
- Validate stock quantity and user selections.

## 🛠️ Technologies Used

- Programming Language: Java
- Concepts: Arrays, Loops, Conditional Statements, Switch Case
- IDE: Visual Studio Code
- JDK: Java Development Kit

## ⚙️ How to Run

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal.
4. Compile the Java program:

```bash
javac StockTradingPlatform.java
```

5. Execute the program:

```bash
java StockTradingPlatform
```

## 💻 Sample Output

```text
===== STOCK TRADING PLATFORM =====

1. View Stocks
2. Buy Stock
3. Sell Stock
4. View Portfolio
5. Exit

Enter choice: 1

Available Stocks:
TCS - Rs.3500
INFOSYS - Rs.1500
WIPRO - Rs.500

Enter choice: 2
Enter stock number: 1
Enter quantity: 2

Stock purchased successfully!

Enter choice: 4

===== MY PORTFOLIO =====
Available Balance: Rs.93000
TCS Quantity: 2
INFOSYS Quantity: 0
WIPRO Quantity: 0
```

## 🔄 Working Principle

1. The application displays available stocks.
2. The user selects a stock.
3. The user enters the quantity to buy.
4. The system checks the available balance.
5. The stock quantity and balance are updated.
6. Users can sell their owned stocks.
7. The portfolio displays the updated stock holdings.

## 🎓 Learning Outcomes

- Understanding Java arrays.
- Implementing switch-case statements.
- Learning basic stock trading operations.
- Managing portfolio data.
- Applying conditional statements and loops.
- Developing menu-driven Java applications.

## ⚠️ Note

This is an educational stock trading simulation. It uses predefined stock names and prices. It does not connect to real-time stock market data or perform actual financial transactions.

## 👨‍💻 Internship Details

**CodeAlpha – Java Programming Internship**

Task 2: Stock Trading Platform.

This project is developed as part of the CodeAlpha Java Programming Internship.

## 📜 License

This project is created for educational and internship purposes.
