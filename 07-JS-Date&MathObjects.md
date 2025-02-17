```js

Day 7: Date & Math Objects (M)

1. WORKING WITH DATES

  • Date Creation
    Using new Date() constructs a Date object that represents the current date and time or a specified date when a valid date string is provided.
    For instance, new Date("2020-01-01") creates a Date object for January 1, 2020.

  • Getting & Setting Date Components
    Retrieve individual parts of a date using methods like getDate(), getMonth(), getFullYear(), getHours(), among others.
    Modify specific date components using corresponding set methods such as setDate(), setMonth(), setFullYear(), and setHours().

  • Date Formatting
    Convert Date objects into standardized string formats using toISOString(), which produces an ISO 8601 string.
    Alternatively, use toLocaleDateString() to format dates according to local conventions and display preferences.

  • Basic Date Arithmetic
    Perform operations such as adding days to a given date by adjusting the day component.
    Compare dates to determine their sequence and order.
    Consider time zones and UTC differences for accurate date and time calculations, keeping in mind that local time adjustments may be necessary.

2. MATH OBJECT ESSENTIALS

  • Common Math Methods
    Math.round() rounds a number to the nearest integer.
    Math.ceil() rounds a number upward to the next largest integer.
    Math.floor() rounds a number downward to the next smallest integer.
    Math.abs() returns the absolute (non-negative) value of a number.

  • Generating Random Numbers
    Math.random() produces a pseudo-random number between 0 (inclusive) and 1 (exclusive), which can be scaled to a desired range.

  • Finding Extremes
    Math.max() returns the largest value among a set of numbers.
    Math.min() returns the smallest value among a set of numbers.

  • Other Useful Functions
    Math.pow() performs exponentiation by raising a base number to a given power.
    Math.sqrt() computes the square root of a number.

  • Constants
    Math.PI represents the ratio of a circle's circumference to its diameter, essential for circular calculations.
    Math.E is the base of natural logarithms, useful in various exponential calculations.

3. PRACTICAL PROJECTS

  • Writing a simple random number generator that leverages Math.random() to produce random integers within a specified range.
  • Creating small utilities such as a basic calculator to perform arithmetic operations or a date formatter to convert Date objects into user-friendly formats.

IMPORTANT TIPS & NOTES:
  • A strong grasp of Date methods is essential for handling scheduling, logging, and time-based operations in applications.
  • When working with dates, be mindful of zero-indexed months and time zone differences to avoid common pitfalls.
  • Practice combining Math functions to perform complex calculations and to build robust utilities.
  • Experiment with small projects to reinforce these concepts and explore real-world applications of Date and Math objects in JavaScript.

END OF NOTES
```
