# 📱 Calculator_Application  
-- Directly Committed from GIT BASH --

## 📖 Project Description  
This Java project is a console-based Calculator Application that performs multiple mathematical operations using a modular and structured approach. Each operation is defined in a separate Java file and function. The program also utilizes inbuilt Java exceptions to handle runtime errors gracefully and ensure robust performance.

### ✅ Functionalities Included:
- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ➗ Division  
- 🟥 Square  
- 🧊 Cube  
- √ Square Root  

The project follows standard coding guidelines, includes meaningful comments, and maintains clean and modular code architecture.

---

## 📂 Project Structure  

```
Calculator_Application/  
│── Main.java              # Entry point of the program  
│── Addition.java          # Handles addition functionality  
│── Subtraction.java       # Handles subtraction functionality  
│── Multiplication.java    # Handles multiplication functionality  
│── Division.java          # Handles division functionality  
│── Square.java            # Handles square calculation  
│── Cube.java              # Handles cube calculation  
│── SquareRoot.java        # Handles square root calculation  
│── README.md              # Project documentation and instructions  
```

---

## ⚡ Functions & Methods Description

| File Name         | Method Name             | Description |
|------------------|--------------------------|-------------|
| Addition.java     | `add(double a, double b)`         | Returns the sum of two numbers |
| Subtraction.java  | `subtract(double a, double b)`    | Returns the difference of two numbers |
| Multiplication.java| `multiply(double a, double b)`   | Returns the product of two numbers |
| Division.java     | `divide(double a, double b)`      | Returns the quotient of two numbers. Throws `ArithmeticException` if dividing by zero |
| Square.java       | `square(double a)`                | Returns the square of a number |
| Cube.java         | `cube(double a)`                  | Returns the cube of a number |
| SquareRoot.java   | `squareRoot(double a)`            | Returns the square root of a number. Throws `IllegalArgumentException` if number is negative |

---

## 🛠️ How to Run

1. Open Git Bash or Command Prompt.
2. Navigate to the project folder:
   ```bash
   cd "path_to_your_project_folder"
   ```
3. Compile the program:
   ```bash
   javac Main.java
   ```
4. Run the program:
   ```bash
   java Main
   ```

---

## 🧠 Exception Handling
The application uses Java's built-in exception classes like:
- `ArithmeticException` for division by zero
- `IllegalArgumentException` for square root of negative numbers

Each exception is caught and handled with proper messages to ensure the user is informed of invalid operations.

---

## 🔗 GitHub Repository Link
[Click here to view the repository](https://github.com/Arjun-57561/Application-for-Calculator)

---

---

🎯 **Built with Java**  
💡 **Author**: Arjun  
📘 **Follow clean code principles and comment every block wisely!**
