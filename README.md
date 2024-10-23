# Calculator App

This is a simple calculator application built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations, such as addition, subtraction, multiplication, and division. Additionally, it supports percentage calculations and maintains a history of operations performed.

## Features

- **Basic Operations**: Perform addition, subtraction, multiplication, and division.
- **Percentage Calculation**: Convert percentages into decimal values for calculations.
- **History Tracking**: Keep track of all calculations performed during the session.
- **User-friendly Interface**: Simple and intuitive layout for easy usage.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Installation

To get started with the Calculator App, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/emilRacz21/calculator-javascript.git
   cd calculator-javascript

  2. **Open index.html in your web browser**

## Usage

- Click on the number buttons (0-9) to input numbers.
- Use the operators (+, -, x, ÷) to perform calculations.
- Click on `%` for percentage calculations.
- Use `c` to clear the last digit or `del` to reset all inputs.
- Press `=` to display the result of the operation.
- The history of operations is displayed at the bottom of the calculator.

## Code Explanation

### Variables
- **`firstNum`**: Stores the first number input by the user.
- **`secondNum`**: Stores the second number for operations.
- **`result`**: Holds the result of the calculations.

### Event Listeners
- Click events are added to each button in the calculator for handling input and operations.
- Additional event listeners handle displaying the history and clearing entries.

### Functions
- **`convertPercentToFloat(num)`**: Converts percentage strings into decimal numbers.
- **`operations(e)`**: Handles the logic for performing calculations based on user input.

## Contributions

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
