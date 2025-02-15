# CODING-SAMURAI-INTERNSHIP-TASK-1&2

**Task-1**
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


**Task-2**
**🔢 Simple Calculator**  
*📌 Project Overview*  
This is a basic calculator built in C++ that can perform fundamental arithmetic operations such as addition, subtraction, multiplication, division, and modulus.  
The program provides a menu-driven interface and allows users to perform multiple calculations until they choose to exit.  

✅ Key Features:  
- Supports five arithmetic operations.
- User-friendly menu for selecting operations.
- Uses a loop to allow multiple calculations in one session.
- Handles invalid choices gracefully.

🚀 C++ Concepts Used  
1. Variables & Data Types:
int a, b, operation; → Stores numbers and user choice.
char choice; → Determines if the user wants to continue.
2. Input & Output Handling:
cin >> a; → Takes user input for calculations.
cout << "Addition: " << a + b; → Displays results dynamically.
3. Control Structures:
switch-case → Implements the menu-driven system for selecting operations.
do-while loop → Ensures the calculator runs until the user decides to exit.
default case → Handles invalid operation choices.
4. Arithmetic Operators:
Addition (+), Subtraction (-), Multiplication (*), Division (/), Modulus (%) are used to perform calculations.
5. Looping & Decision Making:
do-while loop → Allows the user to perform multiple calculations in one session.
6. Basic Error Handling:
The program prevents abrupt termination due to invalid user choices.
Handles division by zero indirectly (though explicit validation can be added)

💡 Learning Outcomes  
By working on this project, I've gain hands-on experience with:  
✅ C++ basic syntax & structure  
✅ User input handling (cin, cout)  
✅ Decision-making (switch-case)  
✅ Looping (do-while)  
✅ Arithmetic operations & expressions  
✅ Error handling for invalid choice  
