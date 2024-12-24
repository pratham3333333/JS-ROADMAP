

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

