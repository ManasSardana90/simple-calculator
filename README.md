# Simple Calculator

This is a simple calculator application built with React for educational purposes. The application allows users to perform basic arithmetic operations.

## Instructions

Follow these steps to set up and run the application:

### 1. Clone the Repository

```bash
git clone https://github.com/ManasSardana90/simple-calculator.git
cd simple-calculator
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Application

```bash
npm start
```

### 4. Implement the Calculator

Open `src/Calculator.js` to implement the following functions:

- **handleDigitClick**: This function should append the clicked digit to the `display` state.
- **handleOperationClick**: This function should append the clicked operation (e.g., +, -, *, /) to the `display` state.
- **calculateResult**: This function should evaluate the expression in the `display` state and set the `result` state.

## Code Explanation

- `Calculator.js`: Contains the main logic for the calculator.
- `App.js`: The root component that renders the `Calculator` component.
- `index.js`: The entry point of the React application.
- `index.html`: The HTML template for the React application.

Feel free to explore and modify the code to enhance the calculator's functionality.

## Useful VS Code Extensions

- **ESLint**: Integrates ESLint into VS Code for JavaScript and JSX linting.
- **Prettier - Code formatter**: An opinionated code formatter for consistent code style.
- **Bracket Pair Colorizer**: A customizable extension for colorizing matching brackets.
