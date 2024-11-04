### 1. Simple Logging
**Task:** Log a basic message to the console.

```javascript
// Log the text "Hello, Bootcamp!" to the console
console.log("Hello, Bootcamp!");
```

### 2. Variable Logging
**Task:** Declare a variable called `greeting` with the value "Welcome to JavaScript!" and log it to the console.

```javascript
// Declare the variable and log it
let greeting = "Welcome to JavaScript!";
console.log(greeting);
```

### 3. Logging Multiple Values
**Task:** Declare two variables, `firstName` and `lastName`, with any values you choose. Log a sentence that says "Hello, [firstName] [lastName]!" to the console by combining these variables.

```javascript
// Declare variables and log them in a sentence
let firstName = "Nabila";
let lastName = "Smith";
console.log("Hello, " + firstName + " " + lastName + "!");
```

### 4. Logging Calculations
**Task:** Write code that calculates the sum of two numbers, `5 + 10`, and logs the result to the console along with a descriptive message.

```javascript
// Perform calculation and log the result with a message
let sum = 5 + 10;
console.log("The sum of 5 and 10 is: " + sum);
```

### 5. Basic Variable Declaration with `let`
**Task:** Use `let` to declare a variable called `age` and assign it a value of `25`. Then, update `age` to `26` and log it to the console.

```javascript
// Declare a variable with let, reassign it, and log the result
let age = 25;
age = 26;
console.log("Updated age:", age);  // Should output: 26
```

**Explanation:** `let` allows you to reassign the value of `age`, which is why this works without error.

---

### 6. Basic Constant Declaration with `const`
**Task:** Use `const` to declare a variable called `birthYear` and assign it a value of `1995`. Attempt to change the value to `1996` and observe what happens.

```javascript
// Declare a constant and attempt to reassign it
const birthYear = 1995;
// Uncomment the line below to test what happens
// birthYear = 1996; // This will cause an error
console.log("Birth year:", birthYear);  // Should output: 1995
```

**Explanation:** `const` creates a constant value that cannot be reassigned. Attempting to change `birthYear` will cause an error.

### 7. Basic Template Literal
**Task:** Repeat the previous exercise, but this time use a template literal to create the greeting message "Hello, John Doe!" and log it to the console.

```javascript
// Use a template literal to construct the string
let firstName = "John";
let lastName = "Doe";
let greeting = `Hello, ${firstName} ${lastName}!`;
console.log(greeting); // Output: Hello, John Doe!
```

**Explanation:** Template literals make it easier to combine variables and strings by using `${variable}` inside backticks (` `), improving readability.

---

### 8. Greeting with Current Year
**Task:** Create a greeting message using a template literal that includes the current year. Declare a variable `name` with the value "Taylor" and a variable `year` with the current year. Log "Hello, Taylor! Welcome to the year 2024."

```javascript
// Simple greeting with template literal
let name = "Taylor";
let year = 2024;
console.log(`Hello, ${name}! Welcome to the year ${year}.`);
// Output: Hello, Taylor! Welcome to the year 2024.
```

### 9. Simple `if` Statement
**Task:** Write an `if` statement that checks if a variable `temperature` is greater than 30. If true, log "It's hot outside."

```javascript
// Simple if statement
let temperature = 35;
if (temperature > 30) {
  console.log("It's hot outside.");
}
```

**Explanation:** This exercise introduces the basic `if` structure, checking a condition and executing a single statement if it's true.

---

### 10. Basic `if/else` Statement
**Task:** Write an `if/else` statement that checks if a variable `isRaining` is true. If true, log "Take an umbrella"; otherwise, log "No umbrella needed."

```javascript
// Basic if/else statement
let isRaining = false;
if (isRaining) {
  console.log("Take an umbrella.");
} else {
  console.log("No umbrella needed.");
}
```

**Explanation:** This exercise demonstrates the use of `if` with an `else` clause for binary conditions.

---

### 11. `if/else` with Comparison
**Task:** Write an `if/else` statement that checks if a variable `age` is 18 or older. If true, log "You are eligible to vote." Otherwise, log "You are not eligible to vote."

```javascript
// If/else with comparison
let age = 17;
if (age >= 18) {
  console.log("You are eligible to vote.");
} else {
  console.log("You are not eligible to vote.");
}
```

**Explanation:** This exercise practices using comparison operators within `if` conditions.

---

### 12. `if/else if/else` Chain
**Task:** Write an `if/else if/else` statement that checks a variable `score`. If `score` is 90 or above, log "Grade: A". If `score` is 80-89, log "Grade: B". Otherwise, log "Grade: C".

```javascript
// If/else if/else chain
let score = 85;
if (score >= 90) {
  console.log("Grade: A");
} else if (score >= 80) {
  console.log("Grade: B");
} else {
  console.log("Grade: C");
}
```

**Explanation:** This example introduces multiple conditions with `else if` to evaluate more than two scenarios.

---

### 13. Combined Conditions with Logical Operators
**Task:** Declare two variables, `isMember` with the value `true` and `purchaseAmount` with the value `150`. Write an `if` statement that checks if `isMember` is `true` and `purchaseAmount` is greater than 100. If both are true, log "You qualify for a discount".

```javascript
// Combining comparison with logical AND
let isMember = true;
let purchaseAmount = 150;
if (isMember && purchaseAmount > 100) {
  console.log("You qualify for a discount.");
}
```

**Explanation:** This exercise combines comparison operators with a logical operator (`&&`) to check multiple conditions together.

### 14. Basic `for` Loop with Counting
**Task:** Write a `for` loop that logs the numbers from 1 to 5.

```javascript
// Basic for loop counting up
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

**Explanation:** This exercise introduces the `for` loop structure and uses it to count up from 1 to 5.

---

### 15. Counting Down with a `for` Loop
**Task:** Write a `for` loop that logs the numbers from 5 down to 1.

```javascript
// For loop counting down
for (let i = 5; i >= 1; i--) {
  console.log(i);
}
```

**Explanation:** This example reinforces the `for` loop structure, but with a decrementing loop to count down.

---

### 16. Summing Numbers with a `for` Loop
**Task:** Write a `for` loop to calculate the sum of numbers from 1 to 10 and log the result.

```javascript
// Summing numbers from 1 to 10
let sum = 0;
for (let i = 1; i <= 10; i++) {
  sum += i;
}
console.log("Sum:", sum); // Should output 55
```

**Explanation:** This exercise uses a `for` loop to repeatedly add numbers to a `sum` variable, reinforcing basic math operations within loops.

---

### 17. Simple Function with No Parameters
**Task:** Write a function called `greet` that logs "Hello, world!" when called.

```javascript
// Simple function with no parameters
function greet() {
  console.log("Hello, world!");
}
greet(); // Output: Hello, world!
```

**Explanation:** This exercise introduces a basic function with no parameters, helping students practice defining and calling functions.

---

### 18. Function with One Parameter
**Task:** Write a function called `square` that takes a number as a parameter, squares it, and returns the result. Call the function with any number and log the result.

```javascript
// Function with one parameter
function square(number) {
  return number * number;
}
console.log(square(5)); // Output: 25
```

**Explanation:** This example demonstrates how to create a function that takes an argument, performs a calculation, and returns a result.

---

### 19. Function with Multiple Parameters
**Task:** Write a function called `add` that takes two numbers as parameters, adds them together, and returns the result. Call the function with any two numbers and log the result.

```javascript
// Function with multiple parameters
function add(a, b) {
  return a + b;
}
console.log(add(10, 15)); // Output: 25
```

**Explanation:** This exercise introduces functions with multiple parameters and reinforces the use of `return` to send results back to the caller.

---

### 20. Positive, Negative, or Zero Check
**Task:** Write a function called `checkNumber` that takes a number as a parameter. The function should:
- Return "Positive" if the number is greater than 0.
- Return "Negative" if the number is less than 0.
- Return "Zero" if the number is exactly 0.

Call the function with different values and log the result.

```javascript
// Function with conditional logic without modulo
function checkNumber(number) {
  if (number > 0) {
    return "Positive";
  } else if (number < 0) {
    return "Negative";
  } else {
    return "Zero";
  }
}

console.log(checkNumber(10));  // Output: Positive
console.log(checkNumber(-5));  // Output: Negative
console.log(checkNumber(0));   // Output: Zero
```

**Explanation:** This example uses simple conditional logic to classify a number without relying on the modulo operator. It checks whether the number is greater than, less than, or equal to zero.

### 21. Level Up - Function with Conditional Logic
**Task:** Write a function called `isEven` that takes a number as a parameter and returns `true` if the number is even and `false` if it’s odd. Call the function with any number and log the result.

```javascript
// Function with conditional logic
function isEven(number) {
  if (number % 2 === 0) {
    return true;
  } else {
    return false;
  }
}
console.log(isEven(8)); // Output: true
console.log(isEven(7)); // Output: false
```

**Explanation:** This exercise adds conditional logic within a function, helping students practice decision-making within a function context.


