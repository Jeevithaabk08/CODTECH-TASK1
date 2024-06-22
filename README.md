# CODTECH-TASK1


Name: JEEVITHAA B K
Company: CODTECH IT SOLUTIONS
ID:CT08DS1995
Domain: Java Programming
Duration: JUNE TO JULY 2024

### Overview of the Simple Calculator Project

#### Project Description
The Simple Calculator project is a basic command-line Java application that allows users to perform fundamental arithmetic operations. The calculator can handle addition, subtraction, multiplication, and division of two numbers input by the user.

#### Key Features
- **User Input**: The program prompts the user to input two numbers.
- **Operation Selection**: The user selects an arithmetic operation (addition, subtraction, multiplication, division).
- **Calculation and Output**: The program performs the selected operation on the two numbers and outputs the result.
- **Error Handling**: The program includes basic error handling, such as preventing division by zero.

#### How It Works
1. **User Input**: The user is prompted to enter the first and second numbers.
2. **Operation Selection**: The user is asked to choose an arithmetic operation by entering one of the following characters: `+`, `-`, `*`, `/`.
3. **Switch Case for Operations**: The program uses a `switch` statement to determine which operation to perform based on the user's input.
4. **Perform Calculation**:
    - For addition (`+`), it adds the two numbers.
    - For subtraction (`-`), it subtracts the second number from the first.
    - For multiplication (`*`), it multiplies the two numbers.
    - For division (`/`), it divides the first number by the second, ensuring the second number is not zero to avoid division by zero errors.
5. **Output Result**: The result of the operation is displayed to the user.
6. **Error Handling**: If an invalid operation is selected, or if division by zero is attempted, an appropriate error message is displayed.

#### Tools and Technologies
- **Java Programming Language**: The program is written in Java.
- **Scanner Class**: Used to capture user input from the console.

#### Steps to Run the Program
1. **Set Up**: Ensure you have a Java Development Kit (JDK) installed on your machine.
2. **Write Code**: Copy the provided Java code into a file named `SimpleCalculator.java`.
3. **Compile**: Open a terminal or command prompt, navigate to the directory containing `SimpleCalculator.java`, and compile the program using the command `javac SimpleCalculator.java`.
4. **Execute**: Run the compiled program using the command `java SimpleCalculator`.
5. **Interact**: Follow the prompts to input numbers and choose an arithmetic operation. The result will be displayed on the console.

#### Example Usage
```
Enter the first number: 10
Enter the second number: 5
Choose an operation (+, -, *, /): +
The result of addition is: 15.0
```

### Project Extension Ideas
- **Multiple Operations**: Allow the user to perform multiple operations in sequence without restarting the program.
- **Enhanced Error Handling**: Improve error messages and handling for non-numeric inputs.
- **Graphical User Interface (GUI)**: Create a simple GUI using Java Swing or JavaFX to make the calculator more user-friendly.
- **Additional Operations**: Add more complex mathematical operations like exponentiation, square roots, and trigonometric functions.

This project is a foundational exercise in Java programming, demonstrating basic concepts such as user input, control flow, arithmetic operations, and error handling.
