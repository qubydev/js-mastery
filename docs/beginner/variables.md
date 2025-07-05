# JS Variables

### Resources
- [W3Schools: JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)

### Must Know

#### 1. Which keyword should you use?
The `let` and `const` keywords were introduced in JavaScript (ES6) in 2015. Prior to that, `var` was used for variable declarations, so you may encounter `var` in older codebases.

- Use `let` for variables whose values may change.
- Use `const` for variables with values that should not change. (eg. `const PI = 3.14`)

**Note:** Avoid using `var` unless you are working in an older codebase.

**Note:** Prefer using `const` whenever possible. This helps the JavaScript runtime to optimize variable storage and evaluation.

