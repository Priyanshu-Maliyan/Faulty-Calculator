Faulty Calculator
By Priyanshu Maliyan

Project Description
The Faulty Calculator is a playful calculator with an intentional twist: it sometimes provides incorrect results by randomly switching the mathematical operations. It's designed as a fun, quirky project to simulate calculation errors, making it both entertaining and unpredictable!

Features
Standard Operations:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Exponentiation (**)

Random Faults: Occasionally, based on randomness, the calculator swaps the selected operator with an incorrect one:
+ becomes -
* becomes +
- becomes /
/ becomes **

Randomness Factor: The faulty behavior is triggered when a random number is less than or equal to 0.1. Otherwise, the calculator works normally.

How It Works
The calculator takes three inputs:
First number (a)
Operator (c): Choose from +, -, *, /, **
Second number (b)
A random number is generated between 0 and 1 using Math.random().
If the random number is greater than 0.1, the calculator performs the operation normally.
If the random number is less than or equal to 0.1, the selected operator is swapped with a "faulty" one using a predefined object, which leads to an incorrect result.
Example Output
Correct Calculation (random > 0.1):
Input: 5 + 3
Output: The result is 8
Faulty Calculation (random <= 0.1):
Input: 5 + 3
Output: The result is 2 (because + was replaced by -)

How to Use
Clone the Repository:
bash
Copy code
git clone https://github.com/Priyanshu-Maliyan/Faulty-Calculator
cd faulty-calculator

Run the Code:

You can directly run the JavaScript code in a browser console or embed it into an HTML file for a more user-friendly experience.
Try Different Inputs:

Enter different numbers and operations to see how often the calculator gives you the correct result or a faulty one!
Requirements
Any modern web browser with JavaScript enabled.

Future Enhancements
Graphical User Interface (GUI): Create a more intuitive interface instead of relying on prompts and alerts.
Toggle for Faulty Mode: Add an option to enable or disable the faulty behavior.
Additional Operations: Implement more complex operations like square roots, logarithms, etc.
