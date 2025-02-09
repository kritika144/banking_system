# banking_system
A basic banking system using Java and OOP principles, managing accounts via a HashMap. It allows users to create accounts, deposit money, and view account details with error handling for invalid operations.

*Banking System in Java
Overview  
A simple banking system implemented in Java using Object-Oriented Programming (OOP). The system manages bank accounts with features like account creation, money deposit, and account information retrieval. Accounts are stored in a `HashMap` for fast access, with error handling for invalid operations.

Features
- Account Management: Create accounts with account number, customer name, and balance.
- Deposit: Deposit money into existing accounts.
- Account Info: View account details (account number, customer name, balance).
- Error Handling: Validates transactions and displays appropriate error messages.

Technologies 
- Java: Core language for implementation.
- HashMap: Stores account information for quick lookup.

How It Works
1. Create Account: Accounts are added using an account number, customer name, and balance.
2. Deposit: Deposits are added to an existing account balance.
3. View Account Info: Displays account details or an error if the account is not found.
4. Error Handling: Invalid accounts or transactions trigger error messages.

Code Structure  
- Bank Class: Manages accounts with methods to add, display, and perform transactions.
- Account Class: Represents individual accounts with attributes and deposit functionality.

Sample Output
```
Transaction successful. Updated balance: $1500.0
Account not found!
Account Number: 101
Customer Name: Neha Jain
Balance: $1500.0
```

Future Enhancements
- Withdrawals: Add withdrawal functionality.
- Account Types: Support for various account types (savings, checking).
- GUI: Implement a graphical user interface.
- Database: Integrate with a database for persistent storage.
- Security: Add authentication for user login.

How to Run  
1. Clone the repository or paste the code into your IDE.
2. Compile and run the `banking_system` class to simulate account operations.

Conclusion  
A foundational banking system using Java and OOP principles. The project is scalable and can be expanded with additional features like withdrawals, security, and database integration.
