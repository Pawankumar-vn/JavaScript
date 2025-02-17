```js

Day 1: JavaScript Basics (E)

1. INTRODUCTION TO JAVASCRIPT

  • JavaScript is a high-level, interpreted programming language essential for web development.
    It enables dynamic content, interactive features, and complex functionalities on web pages.

  • It runs on both the client-side (in web browsers) and server-side (using environments like Node.js).

2. VARIABLES

  • Variables are containers used to store data values.
    They allow you to label and reference data that may change over time.

  • Declaration Keywords:
    - var: Function-scoped or globally-scoped, hoisted, and can be re-declared.
      var greeting = "Hello"
      Note: var declarations are hoisted, meaning they are processed before code execution.

    - let: Block-scoped, cannot be re-declared in the same block, and is hoisted but not initialized until defined.
      let age = 30
      Use let for variables whose values will change within a specific block.

    - const: Block-scoped, must be initialized at declaration, and its value cannot be reassigned.
      const PI = 3.14159
      Use const for values that remain constant throughout the program.

  • Key Concepts:
    Hoisting and scope differences between var, let, and const are crucial for writing predictable code.

3. DATA TYPES

  • JavaScript supports several data types that define the kind of value a variable holds.

  • Primitive Data Types:
    - String: Represents textual data enclosed in quotes.
      let name = "Alice"
      Strings can be defined using double quotes, single quotes, or backticks for template literals.

    - Number: Represents both integers and floating-point numbers.
      let count = 100
      let price = 9.99

    - Boolean: Represents logical values: true or false.
      let isActive = true

    - Null: Represents an intentional absence of any object value.
      let result = null

    - Undefined: Indicates a variable that has been declared but not assigned a value.
      let notAssigned

    - Symbol: Represents a unique and immutable identifier, useful for object property keys.
      let id = Symbol("id")

    - BigInt: Represents integers with arbitrary precision for very large numbers.
      let bigNumber = 123456789012345678901234567890n

  • Checking Data Types:
    Use the typeof operator to determine the data type of a variable.
      typeof name  returns "string"

4. OPERATORS

  • Operators perform operations on variables and values, enabling arithmetic, assignment, comparisons, and logic.

  • Arithmetic Operators:
    Addition (+), Subtraction (-), Multiplication (*), Division (/), and Modulus (%)
      let sum = 5 + 3
      let remainder = 10 % 3
    Exponentiation Operator (**)
      let power = 2 ** 3  evaluates to 8

  • Assignment Operators:
    Basic Assignment (=) and Compound Assignments (+=, -=, *=, /=, %=)
      let x = 10
      x += 5  updates x to 15

  • Comparison Operators:
    Equality (==) vs. Strict Equality (===):
      5 == "5" returns true due to type coercion
      5 === "5" returns false because the types differ
    Other Operators include !=, !==, >, <, >=, <=.

  • Logical Operators:
    Logical AND (&&), Logical OR (||), and Logical NOT (!)
      true && false returns false
      !true returns false
    Note: Logical operators use short-circuit evaluation, meaning later expressions may not be evaluated if the result is determined by the earlier ones.

  • Ternary Operator:
    A concise conditional operator using the syntax:
      condition ? expressionIfTrue : expressionIfFalse
      let status = (age >= 18) ? "Adult" : "Minor"

5. TYPE CONVERSION

  • Type Conversion is the process of converting a value from one data type to another, which can be done explicitly or implicitly.

  • Explicit Conversion Methods:
    Number() converts a value to a number.
      let num = Number("123")  converts the string "123" to the number 123
    String() converts a value to a string.
      let str = String(123)  converts the number 123 to "123"
    Boolean() converts a value to a boolean.
      let bool = Boolean(0)  converts 0 to false
    parseInt() converts a string to an integer.
      let integer = parseInt("50px")  extracts 50 as an integer
    parseFloat() converts a string to a floating-point number.
      let floatNum = parseFloat("3.14em")  extracts 3.14 as a float

  • Implicit Conversion:
    JavaScript may automatically convert types during operations.
      "5" + 1 results in "51" due to string concatenation

IMPORTANT TIPS & NOTES:
  • Start with the basics and build a strong foundation in variable declaration, data types, operators, and type conversion.
  • Always prefer let and const over var for better scope management and code reliability.
  • Use strict equality (===) to avoid unexpected type coercion.
  • Experiment with small code snippets to understand how JavaScript handles different data types and operations.
  • As you progress, explore additional topics like functions, arrays, objects, and control structures to expand your JavaScript knowledge.

END OF NOTES

```
