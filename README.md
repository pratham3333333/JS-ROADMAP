
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
