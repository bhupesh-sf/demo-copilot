# Calculator Project

This project is a simple calculator implemented in JavaScript.

## Usage

```javascript
const Calculator = require('./calc.js');

const calculator = new Calculator();
calculator.add(5).subtract(3).multiply(2).divide(1);
console.log(calculator.getResult()); // Outputs: 4
