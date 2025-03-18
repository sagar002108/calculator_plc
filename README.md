Prefix Expression Calculator
Overview
This is a Python-based Prefix Expression Calculator that evaluates mathematical expressions given in prefix notation (also known as Polish notation). It supports the + (addition) and * (multiplication) operators and converts prefix expressions into infix notation while computing the result.

Features
Evaluates prefix expressions.
Converts prefix notation to infix notation.
Handles invalid expressions with error messages.
Provides a command-line interface for user input.
Requirements
Python 3.x
Installation
No additional libraries are required. Simply download calculator.py and run it using Python.

Usage
Run the script from the terminal:

bash
Copy
Edit
python calculator.py
Enter a prefix expression when prompted, ensuring that the expression is space-separated. For example:

plaintext
Copy
Edit
Enter prefix expression (space-separated): + 3 * 4 5
Example Calculation
Input:

diff
Copy
Edit
+ 3 * 4 5
Output:

yaml
Copy
Edit
Result: 23
Infix Notation: (3 + (4 * 5))
Code Structure
evaluate_prefix(expression): Processes prefix expressions iteratively.
PrefixCalculator: A class-based implementation that parses expressions recursively.
main(): Handles user input and calls the evaluation functions.
Error Handling
The program raises errors for:

Invalid tokens (e.g., unsupported characters).
Incorrectly formatted expressions (e.g., missing operands).
Extra tokens after parsing is complete.
Author
This script was originally developed using Google Colab and has been formatted for standalone execution.
