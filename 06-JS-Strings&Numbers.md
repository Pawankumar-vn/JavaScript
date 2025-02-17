```js
Day 6: String & Number Methods (M)

1. STRING MANIPULATION

  • JavaScript provides a wide range of methods for processing and transforming text.
  • The length property returns the number of characters in a string.
  • The toUpperCase() method converts all characters in a string to uppercase for uniform casing.
  • The toLowerCase() method converts all characters in a string to lowercase, which is useful for case-insensitive comparisons.
  • The slice() method extracts a portion of a string from a specified start index to an end index without modifying the original string. It supports negative indices to count from the end.
  • The substring() method extracts characters between two indices. It does not support negative values and will swap indices if the first is larger than the second.
  • The replace() method searches for a specified substring or pattern and returns a new string with the replacement applied. By default, only the first occurrence is replaced.
  • The split() method divides a string into an array of substrings based on a given separator.
  • The trim() method removes whitespace from both the beginning and the end of a string, which is essential for cleaning up user input or data fetched from external sources.

2. TEMPLATE LITERALS

  • Template literals are enclosed in backticks (`) and offer a powerful syntax for building strings.
  • They support string interpolation, allowing expressions to be embedded directly within the string using ${...}.
  • Template literals also enable multi-line strings without the need for concatenation or special newline characters, which simplifies formatting and improves readability.

3. NUMBER OPERATIONS & METHODS

  • Conversion & Formatting:
    • The toFixed() method formats a number to a specified number of decimal places and returns it as a string. This is especially useful for displaying currency values or measurements with controlled precision.
    • The parseInt() function converts a string into an integer by reading until it encounters a non-numeric character. It can also accept a radix parameter to specify the numeral system.
    • The parseFloat() function converts a string to a floating-point number, handling decimal values accurately.
  • Additional Numeric Tools:
    • The isNaN() function checks whether a value is "Not-a-Number" and returns true if the value cannot be converted to a valid number.
    • Basic arithmetic operations (addition, subtraction, multiplication, division) are built into JavaScript; however, it is important to note that operations involving fractional numbers may result in approximations due to floating-point precision limitations.

4. PRACTICAL EXAMPLES

  • Combining string and number conversions is a common task:
    • Convert user input strings to numeric values using parseInt() or parseFloat() to perform calculations.
    • Format numerical results with toFixed() to control the number of decimal places before presenting them.
    • Use template literals to create dynamic output messages that seamlessly embed both text and calculated values, for example, constructing a message that displays the result of a calculation.
  • These techniques are fundamental when building utilities like calculators, financial applications, or any program that requires formatted and precise output.

IMPORTANT TIPS & NOTES:
  • Mastering string manipulation methods is crucial for effective data processing, validation, and display in web applications.
  • Understanding the differences between slice() and substring() helps choose the appropriate method for extracting parts of a string.
  • Be mindful of the floating-point precision issues in JavaScript; use appropriate rounding methods to ensure numerical accuracy.
  • Template literals greatly enhance code readability by reducing complex concatenation and making it easier to embed expressions.
  • Regular practice with these methods will build a solid foundation for handling both textual and numerical data in real-world projects.

END OF NOTES

```
