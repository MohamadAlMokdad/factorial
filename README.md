# 🌟 Factorial Calculator

This Python program prompts the user to enter a non-negative integer (`n`) and calculates the **factorial** of that number. The factorial of a number \( n \) is the product of all positive integers up to `n`. Factorials are commonly used in mathematics, especially in probability and combinatorics. 📊

## 📋 Example Output

For example, if you enter `n = 5`, the output will be:

Enter a Number: 5 

Output: 120

## 📖 How It Works

The factorial of a number `n` is calculated recursively:
- **Base case:** If `n = 0`, the function returns `1` (since \(0! = 1\)).
- **Recursive case:** If `n > 0`, the function returns `n * factorial(n - 1)`.

## 🧑‍💻 Usage

1. Run the program and enter a non-negative integer.
2. The program will display the factorial of the entered number.

This is a simple, recursive approach to calculating factorials in Python.
