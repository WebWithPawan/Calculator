Calculator Web App

This is a simple calculator web application built with HTML, CSS, and JavaScript. It provides basic arithmetic functions such as addition, subtraction, multiplication, division, as well as the ability to clear the display and delete the last entered character.

Features
Basic Arithmetic Operations:
Addition (+), Subtraction (-), Multiplication (*), Division (/)
Clear:
AC button to clear the display.
Delete:
DE button to remove the last character entered.
Decimal Point:
A . button to enter decimal points.
Evaluate:
= button to evaluate the expression entered.
Keyboard Input Support:
Users can type directly into the display for a quicker interaction.
Structure
1. HTML (index.html)
The Layout:
The calculator layout consists of buttons for numbers (0-9), arithmetic operators, a decimal point, and an equal sign to perform calculations.
A text input field is used to display the numbers and operations entered.
Form:
A <form> element wraps the calculator UI but does not submit anything (it is used for layout).
2. CSS (style.css)
Styling:
The styles are used to create a clean, simple, and visually appealing layout.
Buttons are styled to look like typical calculator keys, with different color codes for operators and numbers.
3. JavaScript (Inline within HTML)
Basic Interactions:
Button clicks are handled by JavaScript functions attached to the onclick attribute of the buttons.
The eval() function is used to evaluate the mathematical expression entered in the display field when the "=" button is clicked.
The AC button clears the display and the DE button removes the last character.
How to Use
Basic Arithmetic: Click the number buttons and operator buttons to form an arithmetic expression.
Evaluate the Expression: Press the = button to calculate the result.
Clear Display: Use the AC button to clear the display.
Delete Last Character: Use the DE button to delete the last character entered.
Decimal Points: Use the . button to add decimal points in your numbers.
Dependencies
