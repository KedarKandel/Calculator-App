 ## Calculator-App
 
This is a simple calculator app built with React. It allows users to perform  arithmetic calculations.

How to Use
To use the calculator, simply click on the buttons on the screen. The calculator has the following features:

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Decimal point (.)
- Clear (AC)
- Delete (DEL)

To perform a calculation, enter the first operand, then select the operation, and finally enter the second operand. Once both operands have been entered, click the equals (=) button to perform the calculation.

## Installation
To run this app on your local machine, follow these steps:

- Clone the repository: git clone https://github.com/kedarKandel/Calculator-App.git
- Navigate to the project directory: cd Calculator-App
- Install the dependencies: npm install
- Run the app: npm start
- The app should now be running on http://localhost:3000.

Technologies Used
This app was built with the following technologies:

React
HTML/CSS
Code Overview
The app is made up of two components: DigitButton and OperationButton. These components are used to create the calculator buttons. The main component is App, which is responsible for handling user input and displaying the results of calculations.

The state of the calculator is managed using the useReducer hook. The reducer function is responsible for updating the state based on the user's actions. The evaluate function is used to perform the actual calculations.
