# CODING-SAMURAI-INTERNSHIP-TASK-1

**Bank Account Management System 🏦**  
*Overview*  
This project is a Bank Account Management System developed in C++ as part of an internship task. It provides basic banking functionalities such as:  
✅ Creating an account  
✅ Depositing money  
✅ Withdrawing funds  
✅ Checking balance  
✅ Transferring funds between accounts (if implemented)  
The system uses file handling to store and retrieve account details, ensuring data persistence across sessions.  

Features  
🔹 Object-Oriented Design: Implements classes and objects to manage bank accounts.  
🔹 File Handling: Uses ifstream and ofstream to store and update account data.    
🔹 User Authentication (Basic): Ensures only valid account numbers can perform transactions.  
🔹 Error Handling & Validation: Prevents overdrafts and invalid inputs.  
🔹 Data Persistence: All account details are stored in a text file for future access.

Technologies Used  
- Programming Language: C++
- Concepts Applied:
  - Classes & Objects
  - Constructors & Encapsulation
  - File Handling (ifstream, ofstream)
  - Conditional Logic & Loops
  - Error Handling

Follow the on-screen prompts to:  
- Create an account – Enter account details to register.
- Deposit money – Add funds to your account.
- Withdraw money – Withdraw funds while ensuring sufficient balance.
- Check balance – View the current balance of your account.

Code Structure  
📂 Bank-Account-Management-System/  
 📜 bank_system.cpp → Main C++ source code  
 📜 accounts.txt → File storing account data (created automatically)  
 📜 README.md → Project documentation

Future Enhancements 🚀  
🔹 Add password protection for accounts  
🔹 Implement database support (MySQL, SQLite) instead of text files  
🔹 Develop a graphical user interface (GUI) using Qt or another framework  
🔹 Introduce account transaction history logs

License  
This project is open-source and available under the MIT License.
