# JS Operators

**NOTE:** Please ignore the section ***"JavaScript Bitwise Operators"***, you would almost never need those (Offcourse, you can learn whenever it is required).

### Resources
- [https://www.w3schools.com/js/js_operators.asp](https://www.w3schools.com/js/js_operators.asp)

### Must Know

#### 1. Why `"5" + 5 -> 55`?
This operation is called *concatination*. You do'nt need to worry too much about it now, we will see that in details soon.

### 2. Ternary Operator (`?`)

The ternary operator is a very important and useful operator in JavaScript. It acts as a shorthand for `if...else` statements.

**Syntax:**
```javascript
condition ? expressionIfTrue : expressionIfFalse;
````

**Example:**

```javascript
let age = 18;
const status = age >= 18 ? "Adult" : "Minor";
console.log(status); // "Adult"
```




