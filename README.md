# Calculator
Java calculator app
It allows the user to input two numbers and choose an arithmetic operation to perform.

📌 Features

Accepts two user-input numbers

Supports four basic arithmetic operations:

Addition

Subtraction

Multiplication

Division

Includes validation to prevent division by zero

Displays descriptive prompts and results

🛠️ How It Works

The program asks the user to enter the first number.

It prompts for the second number.

A menu appears asking the user to choose an operation (1–4).

Based on the choice, the calculator performs the selected operation.

The result is printed to the console.

If an invalid option is selected or division by zero is attempted, the program displays an appropriate error message.

📂 Code Structure

The project contains a single Java file:

day3/
 └── Calculator.java


The main method handles:

User input using Scanner

Operation selection

Arithmetic calculations

Error handling

▶️ Running the Program
Prerequisites

Java Development Kit (JDK) installed (version 8 or above)

Steps

Open a terminal/command prompt.

Navigate to the folder containing Calculator.java.

Compile the program:

javac Calculator.java


Run the program:

java Calculator

📘 Example Usage
Enter the first number
10
Enter the second number
5
Choose the operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
1
Result: 15.0

🧩 Error Handling

If the user selects an invalid menu option → "Invalid choice"

If attempting to divide by zero → "Error: Division by zero is not allowed"

💡 Possible Enhancements

Add loop to allow repeated calculations

Add more operations (modulus, exponent, etc.)

Wrap logic in reusable methods

Improve input validation
