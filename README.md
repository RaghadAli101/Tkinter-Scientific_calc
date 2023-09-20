# Tkinter-Scientific_calc
This document provides documentation for a simple calculator application implemented in Python using the tkinter library. The calculator supports basic arithmetic operations and trigonometric functions.


Calculator Application Documentation

Table of Contents:
1. Application Setup
2. User Interface
3. Button Functions
4. Error Handling
5. About Menu
6. Conclusion

1. Application Setup:
   - The application is created using the tkinter library.
   - It features a graphical user interface (GUI) for performing calculations.
   - The GUI includes an input screen for displaying expressions and results.

2. User Interface:
   - The calculator interface consists of a screen (Entry widget) for input and displaying results.
   - Buttons are provided for digits (0-9), arithmetic operators (+, -, *, /, %), parentheses, trigonometric functions (sin, cos, tan), constants (pi), and special functions (log, exp, log10).

3. Button Functions:
   - Buttons are defined with associated functions.
   - Numeric buttons append their respective values to the input screen.
   - Arithmetic operator buttons add the corresponding operator to the input screen.
   - Special buttons (Clr and =) trigger specific actions:
     - "Clr" clears the input screen.
     - "=" evaluates the expression and displays the result.
   - Trigonometric buttons calculate trigonometric functions for the given input.
   - Parentheses, constants, and special functions add their respective values to the input screen.

4. Error Handling:
   - The calculator handles calculation errors gracefully.
   - If an error occurs during evaluation (e.g., division by zero), it displays an error message for 3 seconds before clearing the input screen.
   - The status bar shows "Preparing..." during the error delay and "Ready.." afterward.

5. About Menu:
   - The application includes an "About" menu in the top menu bar.
   - The "Terms of Use" option displays information about terms and conditions.
   - The "Send Feedback" option prompts users for feedback and provides a response based on their choice.

6. Conclusion:
   - This Python calculator application offers basic and scientific calculator features using the tkinter library.
   - Users can perform calculations, including arithmetic operations and trigonometric functions, with ease.
   - The calculator handles errors gracefully, provides user feedback, and allows users to send feedback.

Note: This documentation provides an overview of the code structure and functionality. Detailed code comments can be found within the Python script for a more comprehensive understanding of the implementation.


