
# ✨ JavaScript Arithmetic Operators ➕➖✖️➗

This document provides examples of JavaScript arithmetic operators with simple and interactive code snippets.

---

## 📋 Arithmetic Operators Table

| Operator | Description           | Example      | Result |
|----------|-----------------------|--------------|--------|
| `+`      | Addition              | `5 + 3`      | `8`    |
| `-`      | Subtraction           | `5 - 3`      | `2`    |
| `*`      | Multiplication        | `5 * 3`      | `15`   |
| `/`      | Division              | `6 / 3`      | `2`    |
| `%`      | Modulus (Remainder)   | `5 % 2`      | `1`    |
| `**`     | Exponentiation (Power)| `5 ** 2`     | `25`   |

---

## 🖥️ Examples of JavaScript Arithmetic Operators

### 1️⃣ **Addition (`+`)**
The `+` operator adds two numbers together.

```javascript
let a = 5;
let b = 3;
console.log(a + b); // Output: 8
```

---

### 2️⃣ **Subtraction (`-`)**
The `-` operator subtracts the second number from the first.

```javascript
let a = 5;
let b = 3;
console.log(a - b); // Output: 2
```

---

### 3️⃣ **Multiplication (`*`)**
The `*` operator multiplies two numbers.

```javascript
let a = 5;
let b = 3;
console.log(a * b); // Output: 15
```

---

### 4️⃣ **Division (`/`)**
The `/` operator divides the first number by the second.

```javascript
let a = 6;
let b = 3;
console.log(a / b); // Output: 2
```

---

### 5️⃣ **Modulus (`%`)**
The `%` operator returns the remainder of the division.

```javascript
let a = 5;
let b = 2;
console.log(a % b); // Output: 1
```

---

### 6️⃣ **Exponentiation (`**`)**
The `**` operator raises the first number to the power of the second.

```javascript
let a = 5;
let b = 2;
console.log(a ** b); // Output: 25
```

---


# ✍️ JavaScript Assignment Operators 🖥️

This document explains **JavaScript Assignment Operators** with brief descriptions and code examples.

---

## 📋 Assignment Operators Table

| Operator | Description                       | Example         | Equivalent To      |
|----------|-----------------------------------|-----------------|--------------------|
| `=`      | Assigns a value to a variable     | `x = 5`         | `x = 5`           |
| `+=`     | Adds and assigns the result       | `x += 3`        | `x = x + 3`       |
| `-=`     | Subtracts and assigns the result  | `x -= 2`        | `x = x - 2`       |
| `*=`     | Multiplies and assigns the result | `x *= 4`        | `x = x * 4`       |
| `/=`     | Divides and assigns the result    | `x /= 2`        | `x = x / 2`       |
| `%=`     | Assigns the remainder of division | `x %= 3`        | `x = x % 3`       |
| `**=`    | Assigns the result of exponentiation | `x **= 2`   | `x = x ** 2`      |

---

## 🖥️ Examples of Assignment Operators

### 1️⃣ **Basic Assignment (`=`)**
Assigns a value to a variable.

```javascript
let x;
x = 5; 
console.log(x); // Output: 5
```

---

### 2️⃣ **Addition Assignment (`+=`)**
Adds a value to the variable and assigns the result.

```javascript
let x = 5;
x += 3; // Same as x = x + 3
console.log(x); // Output: 8
```

---

### 3️⃣ **Subtraction Assignment (`-=`)**
Subtracts a value from the variable and assigns the result.

```javascript
let x = 5;
x -= 2; // Same as x = x - 2
console.log(x); // Output: 3
```

---

### 4️⃣ **Multiplication Assignment (`*=`)**
Multiplies the variable by a value and assigns the result.

```javascript
let x = 5;
x *= 4; // Same as x = x * 4
console.log(x); // Output: 20
```

---

### 5️⃣ **Division Assignment (`/=`)**
Divides the variable by a value and assigns the result.

```javascript
let x = 10;
x /= 2; // Same as x = x / 2
console.log(x); // Output: 5
```

---

### 6️⃣ **Modulus Assignment (`%=`)**
Divides the variable and assigns the remainder.

```javascript
let x = 5;
x %= 3; // Same as x = x % 3
console.log(x); // Output: 2
```

---

### 7️⃣ **Exponentiation Assignment (`**=`)**
Raises the variable to the power of a value and assigns the result.

```javascript
let x = 2;
x **= 3; // Same as x = x ** 3
console.log(x); // Output: 8
```

---


# 🚀 JavaScript Comparison Operators 🔍

This document provides examples of JavaScript comparison operators, showcasing their functionality with simple code snippets.

---

## 📋 Comparison Operators Table

| Operator | Description                             | Example         | Result   |
|----------|-----------------------------------------|-----------------|----------|
| `==`     | Equal to (allows type conversion)       | `5 == '5'`      | `true`   |
| `===`    | Strict equal to (no type conversion)    | `5 === '5'`     | `false`  |
| `!=`     | Not equal to (allows type conversion)   | `5 != '5'`      | `false`  |
| `!==`    | Strict not equal to (no type conversion)| `5 !== '5'`     | `true`   |
| `>`      | Greater than                            | `5 > 3`         | `true`   |
| `<`      | Less than                               | `5 < 3`         | `false`  |
| `>=`     | Greater than or equal to               | `5 >= 5`        | `true`   |
| `<=`     | Less than or equal to                  | `5 <= 3`        | `false`  |

---

## 🖥️ Examples of JavaScript Comparison Operators

### 1️⃣ **Equal to (`==`)**
The `==` operator checks if two values are equal, allowing type conversion.

```javascript
let a = 5;
console.log(a == '5'); // true (type conversion happens)
```

---

### 2️⃣ **Strict Equal to (`===`)**
The `===` operator checks if two values are equal without type conversion.

```javascript
let a = 5;
console.log(a === '5'); // false (different types)
```

---

### 3️⃣ **Not Equal to (`!=`)**
The `!=` operator checks if two values are not equal, allowing type conversion.

```javascript
let a = 5;
console.log(a != '5'); // false (type conversion happens)
```

---

### 4️⃣ **Strict Not Equal to (`!==`)**
The `!==` operator checks if two values are not equal without type conversion.

```javascript
let a = 5;
console.log(a !== '5'); // true (different types)
```

---

### 5️⃣ **Greater Than (`>`)**
The `>` operator checks if the left operand is greater than the right operand.

```javascript
let a = 5;
console.log(a > 3); // true
```

---

### 6️⃣ **Less Than (`<`)**
The `<` operator checks if the left operand is less than the right operand.

```javascript
let a = 5;
console.log(a < 3); // false
```

---

### 7️⃣ **Greater Than or Equal to (`>=`)**
The `>=` operator checks if the left operand is greater than or equal to the right operand.

```javascript
let a = 5;
console.log(a >= 5); // true
```

---

### 8️⃣ **Less Than or Equal to (`<=`)**
The `<=` operator checks if the left operand is less than or equal to the right operand.

```javascript
let a = 5;
console.log(a <= 3); // false
```


# 🔗 JavaScript Logical Operators

JavaScript **Logical Operators** are used to perform logical operations and return Boolean results based on their operands.

---

## 📋 Logical Operators Table

| Operator | Description                       | Example                | Result       |
|----------|-----------------------------------|------------------------|--------------|
| `&&`     | Logical AND (returns `true` if both operands are true) | `true && false` | `false` |
| `||`     | Logical OR (returns `true` if at least one operand is true) | `true || false` | `true`  |
| `!`      | Logical NOT (inverts the Boolean value) | `!true`         | `false` |

---

## 🖥️ Examples of Logical Operators

### 1️⃣ **Logical AND (`&&`)**
The `&&` operator returns `true` if both operands are `true`.

```javascript
let a = true;
let b = false;

console.log(a && b); // Output: false
console.log(a && !b); // Output: true
```

---

### 2️⃣ **Logical OR (`||`)**
The `||` operator returns `true` if at least one operand is `true`.

```javascript
let a = true;
let b = false;

console.log(a || b); // Output: true
console.log(!a || b); // Output: false
```

---

### 3️⃣ **Logical NOT (`!`)**
The `!` operator inverts the Boolean value.

```javascript
let a = true;

console.log(!a); // Output: false
console.log(!false); // Output: true
```

---

## 🌟 Real-World Examples

1. **Form Validation**  
   Use logical operators to validate user input.

   ```javascript
   let username = "Pratham";
   let password = "12345";

   if (username && password) {
       console.log("Form is valid!");
   } else {
       console.log("Please fill all fields.");
   }
   ```

2. **Access Control**  
   Grant access based on multiple conditions.

   ```javascript
   let isAdmin = true;
   let isLoggedIn = true;

   if (isAdmin && isLoggedIn) {
       console.log("Welcome, Admin!");
   } else {
       console.log("Access denied.");
   }
   ```

---

## 📝 Interview Questions with Answers and Solutions

### 1️⃣ **Question**:  
What will be the output of the following code?

```javascript
console.log(true && false || !false);
```

**Answer**:  
`true`

**Solution**:  
1. Evaluate `!false` → `true`.  
2. Evaluate `true && false` → `false`.  
3. Evaluate `false || true` → `true`.

---

### 2️⃣ **Question**:  
Write a condition to check if a user is either an admin or a premium member.

**Solution**:  
```javascript
let isAdmin = false;
let isPremiumMember = true;

if (isAdmin || isPremiumMember) {
    console.log("Access granted.");
} else {
    console.log("Access denied.");
}
```

---

### 3️⃣ **Question**:  
What will the following code return?

```javascript
let a = false;
let b = true;
console.log(a || (b && !a));
```

**Answer**:  
`true`

**Solution**:  
1. Evaluate `!a` → `true`.  
2. Evaluate `b && true` → `true`.  
3. Evaluate `a || true` → `true`.

---

### 4️⃣ **Question**:  
How can you check if a number is in a specific range (e.g., between 10 and 20)?

**Solution**:  
```javascript
let number = 15;

if (number >= 10 && number <= 20) {
    console.log("Number is in the range.");
} else {
    console.log("Number is out of range.");
}
```

---

### 5️⃣ **Question**:  
What is the difference between `&&` and `||` operators in terms of short-circuit evaluation?

**Answer**:  
- `&&` stops evaluating as soon as the first `false` is encountered.  
- `||` stops evaluating as soon as the first `true` is encountered.

**Example**:  
```javascript
let a = false && console.log("This won't execute.");
let b = true || console.log("This won't execute.");
```

---

# JavaScript Ternary Operator 🌟

Welcome to the **JavaScript Ternary Operator** guide! This repository contains everything you need to understand and practice using the ternary operator in JavaScript. It includes examples, explanations, and **interview practice questions** to help you prepare for your next coding interview.

## 📜 Table of Contents

- [Introduction](#introduction)
- [Why Use the Ternary Operator?](#why-use-the-ternary-operator)
- [Examples of Ternary Operator](#examples-of-ternary-operator)
- [10 Interview Practice Questions](#10-interview-practice-questions)
- [Conclusion](#conclusion)

---

## 📝 Introduction

The **ternary operator** in JavaScript is a concise way to perform conditional checks. It evaluates a condition and returns one of two values based on whether the condition is `true` or `false`. It's a shorthand for `if-else` statements and can make your code more compact and readable when used correctly.

---

## 🚀 Why Use the Ternary Operator?

- **Concise**: The ternary operator allows you to express simple conditional logic in a single line.
- **Readability**: For basic conditions, it can make the code easier to read.
- **Assigning Values**: It’s often used for assigning values based on conditions.

---

## 💻 Examples of Ternary Operator

### Example 1: Basic Conditional Check

```javascript
let age = 20;
let canDrive = (age >= 18) ? "Yes" : "No";
console.log(canDrive); // Output: "Yes"
```

**Explanation:**  
The condition `(age >= 18)` checks if the age is greater than or equal to 18. If true, it returns `"Yes"`, otherwise `"No"`.

---

### Example 2: Nested Ternary Operator

```javascript
let score = 85;
let grade = (score >= 90) ? "A" : (score >= 80) ? "B" : (score >= 70) ? "C" : "D";
console.log(grade); // Output: "B"
```

**Explanation:**  
This example shows a nested ternary operator where multiple conditions are checked in sequence.

---

### Example 3: Using the Ternary Operator with Objects

```javascript
let number = 10;
let result = (number % 2 === 0) ? "Even" : "Odd";
console.log(result); // Output: "Even"
```

**Explanation:**  
Here, we check if the number is even or odd and return the corresponding result.

---

## 🎯 10 Interview Practice Questions

1. **What is the ternary operator in JavaScript?**  
   - The ternary operator is a shorthand for `if-else` statements that evaluates a condition and returns one of two values based on whether the condition is true or false.

2. **Can you write an example of a ternary operator?**  
   - Yes, here’s an example:
     ```javascript
     let x = 5;
     let result = (x > 3) ? "Greater" : "Smaller";
     console.log(result); // Output: "Greater"
     ```

3. **How do you handle multiple conditions using the ternary operator?**  
   - You can use nested ternary operators. Example:
     ```javascript
     let age = 25;
     let category = (age < 18) ? "Minor" : (age <= 60) ? "Adult" : "Senior";
     console.log(category); // Output: "Adult"
     ```

4. **What is the advantage of using the ternary operator over an `if-else` statement?**  
   - The ternary operator allows for more concise code, especially when the logic is simple and you need to return or assign values based on conditions.

5. **Can the ternary operator be used for assignments?**  
   - Yes, the ternary operator is often used for assigning values based on conditions, like:
     ```javascript
     let x = 10;
     let result = (x % 2 === 0) ? "Even" : "Odd";
     console.log(result); // Output: "Even"
     ```

6. **How would you rewrite a simple `if-else` statement using a ternary operator?**  
   - For example, converting:
     ```javascript
     if (x > 10) {
       console.log("Greater");
     } else {
       console.log("Smaller");
     }
     ```
     To a ternary operator:
     ```javascript
     console.log((x > 10) ? "Greater" : "Smaller");
     ```

7. **Can the ternary operator return more than just values?**  
   - Yes, it can return functions, objects, or other expressions. Example:
     ```javascript
     let greeting = (user) ? `Hello, ${user}!` : `Hello, Guest!`;
     console.log(greeting); // Output: "Hello, Guest!"
     ```

8. **What happens if you omit one part of the ternary operator?**  
   - Omitting one part will result in a syntax error. The ternary operator requires both the `true` and `false` expressions to function properly.

9. **Is it a good idea to use deeply nested ternary operators? Why or why not?**  
   - It's generally not recommended, as deeply nested ternary operators can make the code harder to read and understand. In such cases, `if-else` statements are preferred for clarity.

10. **What would happen if the ternary operator is used incorrectly, such as missing a colon?**  
    - Missing a colon (`:`) would result in a syntax error, as the ternary operator expects both the `true` and `false` expressions.

---

## 🎉 Conclusion

The **ternary operator** is a great tool to write concise conditional logic in JavaScript. It’s perfect for simple conditions and can make your code more readable when used appropriately. However, avoid overusing nested ternary operators to ensure your code remains clear and easy to understand.




# JavaScript Type Operators 📊

Welcome to the **JavaScript Type Operators** guide! This repository is dedicated to explaining and providing examples of **type operators** in JavaScript. Type operators are used to check and convert data types, which are fundamental for writing robust and error-free code.

## 📜 Table of Contents

- [Introduction](#introduction)
- [Type Operators in JavaScript](#type-operators-in-javascript)
  - [typeof](#typeof)
  - [instanceof](#instanceof)
  - [constructor](#constructor)
  - [Array.isArray](#arrayisarray)
- [10 Interview Practice Questions](#10-interview-practice-questions)
- [Conclusion](#conclusion)

---

## 📝 Introduction

In JavaScript, understanding the **type of data** is crucial for working with variables, functions, and objects. Type operators allow you to check or manipulate the types of values in your code.

---

## 🛠️ Type Operators in JavaScript

### 1. **`typeof` Operator 🔍**

The `typeof` operator is used to check the type of a variable or expression. It returns a string representing the type of the operand.

#### Syntax:
```javascript
typeof operand;
```

#### Example:

```javascript
let name = "John";
console.log(typeof name); // Output: "string"

let age = 30;
console.log(typeof age); // Output: "number"

let isStudent = true;
console.log(typeof isStudent); // Output: "boolean"
```

**Explanation:**
- The `typeof` operator checks the type of `name`, `age`, and `isStudent` and returns their respective types as strings.

---

### 2. **`instanceof` Operator 🔗**

The `instanceof` operator checks if an object is an instance of a specific class or constructor function.

#### Syntax:
```javascript
object instanceof constructor
```

#### Example:

```javascript
let arr = [1, 2, 3];
console.log(arr instanceof Array); // Output: true

let date = new Date();
console.log(date instanceof Date); // Output: true

let obj = {};
console.log(obj instanceof Object); // Output: true
```

**Explanation:**
- The `instanceof` operator checks if the object `arr` is an instance of `Array`, if `date` is an instance of `Date`, and if `obj` is an instance of `Object`.

---

### 3. **`constructor` Property 🏗️**

The `constructor` property of an object refers to the function that created the instance of that object.

#### Example:

```javascript
let person = { name: "Alice", age: 25 };
console.log(person.constructor); // Output: [Function: Object]

let date = new Date();
console.log(date.constructor); // Output: [Function: Date]
```

**Explanation:**
- The `constructor` property points to the function that created the object. For `person`, it's the `Object` constructor, and for `date`, it's the `Date` constructor.

---

### 4. **`Array.isArray()` Method 🧮**

The `Array.isArray()` method is used to check if a value is an array.

#### Syntax:
```javascript
Array.isArray(value);
```

#### Example:

```javascript
let arr = [1, 2, 3];
console.log(Array.isArray(arr)); // Output: true

let notArr = { name: "John" };
console.log(Array.isArray(notArr)); // Output: false
```

**Explanation:**
- `Array.isArray()` checks if the given value is an array. It returns `true` for arrays and `false` for other data types.

---

## 🎯 10 Interview Practice Questions

1. **What does the `typeof` operator do in JavaScript?**
   - The `typeof` operator is used to determine the type of a variable or expression. It returns a string representing the type, such as `"string"`, `"number"`, `"boolean"`, etc.

2. **What is the difference between `typeof` and `instanceof` in JavaScript?**
   - `typeof` is used to check the type of a primitive value (e.g., string, number), while `instanceof` is used to check if an object is an instance of a specific class or constructor function.

3. **How can you check if a value is an array in JavaScript?**
   - You can use `Array.isArray()` to check if a value is an array. Example: `Array.isArray([1, 2, 3])` returns `true`.

4. **What is the purpose of the `constructor` property in JavaScript?**
   - The `constructor` property refers to the function that created the instance of an object. For example, an object created using the `new Date()` constructor will have `Date` as its constructor.

5. **How would you check the type of a variable in JavaScript?**
   - You can use the `typeof` operator to check the type of a variable. Example: `typeof variable`.

6. **What will `typeof null` return in JavaScript?**
   - Surprisingly, `typeof null` returns `"object"`. This is a known JavaScript bug that has been present since its early versions.

7. **How can you check if an object is an instance of a specific constructor function?**
   - You can use the `instanceof` operator. Example: `object instanceof ConstructorFunction`.

8. **Can `typeof` be used to differentiate between an array and an object?**
   - No, `typeof` returns `"object"` for both arrays and objects. To differentiate, you should use `Array.isArray()`.

9. **What would `Array.isArray('hello')` return?**
   - It would return `false`, as a string is not an array.

10. **What is the output of `typeof NaN` in JavaScript?**
    - `typeof NaN` returns `"number"`. Although `NaN` stands for "Not a Number," it is technically considered a number in JavaScript.

---

## 🎉 Conclusion

Type operators in JavaScript, such as `typeof`, `instanceof`, `constructor`, and `Array.isArray()`, are essential tools for checking and manipulating data types. Understanding how and when to use these operators will help you write more reliable and efficient code.

Happy coding! 🚀

---

Here's a properly formatted **GitHub README** file for **JavaScript Logical Operators** practice tasks. It includes interactive **Show Answer** sections, where the answers will be revealed when clicked.

```markdown
# JavaScript Logical Operators Practice 🚀

Welcome to the **JavaScript Logical Operators Practice** guide! This file contains various tasks related to logical operators in JavaScript. Each task has a description, and you can reveal the solutions by clicking on the "Show Answer" button.

## 📜 Table of Contents

- [Task 1: Basic Practice](#task-1-basic-practice)
- [Task 2: Conditional Statements](#task-2-conditional-statements)
- [Task 3: Combining Logical Operators](#task-3-combining-logical-operators)

---

## 🔢 Task 1: Basic Practice (10 minutes)

**Problem:**  
Write a function that checks if a number is between 10 and 20 using the logical AND (`&&`) operator.

```javascript
function checkNumberInRange(number) {
  // Your code here
}
```

<details>
  <summary>Show Answer</summary>

  **Solution:**

  ```javascript
  function checkNumberInRange(number) {
    if (number >= 10 && number <= 20) {
      return "The number is between 10 and 20.";
    } else {
      return "The number is not between 10 and 20.";
    }
  }

  console.log(checkNumberInRange(15)); // Output: "The number is between 10 and 20."
  console.log(checkNumberInRange(25)); // Output: "The number is not between 10 and 20."
  ```

  **Explanation:**
  - The function checks if the number is greater than or equal to 10 **and** less than or equal to 20 using the `&&` logical operator.

</details>

---

## 🗳️ Task 2: Conditional Statements (10 minutes)

**Problem:**  
Create a simple program that checks if a user is allowed to vote based on their age and whether they have an ID.

```javascript
function canVote(age, hasID) {
  // Your code here
}
```

<details>
  <summary>Show Answer</summary>

  **Solution:**

  ```javascript
  function canVote(age, hasID) {
    if (age >= 18 && hasID) {
      return "You are allowed to vote!";
    } else {
      return "You are not allowed to vote.";
    }
  }

  console.log(canVote(20, true)); // Output: "You are allowed to vote!"
  console.log(canVote(17, true)); // Output: "You are not allowed to vote."
  console.log(canVote(20, false)); // Output: "You are not allowed to vote."
  ```

  **Explanation:**
  - The function checks if the user is **18 or older** **and** has an ID using the `&&` logical operator.

</details>

---

## 🔒 Task 3: Combining Logical Operators (10 minutes)

**Problem:**  
Write a function that checks if a person can access a restricted area. The criteria are:
- Must be **over 18** OR have a **special access badge**.
- Must **NOT** be on the restricted list.

```javascript
function canAccessRestrictedArea(age, hasBadge, isRestricted) {
  // Your code here
}
```

<details>
  <summary>Show Answer</summary>

  **Solution:**

  ```javascript
  function canAccessRestrictedArea(age, hasBadge, isRestricted) {
    if ((age > 18 || hasBadge) && !isRestricted) {
      return "Access granted.";
    } else {
      return "Access denied.";
    }
  }

  console.log(canAccessRestrictedArea(25, false, false)); // Output: "Access granted."
  console.log(canAccessRestrictedArea(17, true, false)); // Output: "Access granted."
  console.log(canAccessRestrictedArea(25, false, true)); // Output: "Access denied."
  ```

  **Explanation:**
  - The function checks if the person is either **over 18** or has a **special access badge** using the `||` operator.
  - It also ensures that the person is **not** on the restricted list using the `!` (not) operator.
  
</details>

---

## 🎉 Conclusion

Logical operators are essential in JavaScript for building conditional statements that allow your code to make decisions based on multiple conditions. Practice these tasks to strengthen your understanding of `&&`, `||`, and `!` operators.

---

This format provides a **clean and interactive** way for students to practice coding exercises with easy access to solutions when they need them. If you're hosting this file on GitHub, it will work perfectly with **GitHub Pages** or any Markdown renderer that supports `<details>` and `<summary>` elements.

Let me know if you'd like to add more tasks or explanations!
```
