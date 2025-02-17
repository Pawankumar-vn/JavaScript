```js
Day 2: Control Flow (E)

1. CONDITIONAL STATEMENTS

  • Conditional statements allow execution of different code blocks based on specified conditions.
    They help the program make decisions and perform actions accordingly.

  • if Statement:
    Checks a condition and executes the code block if the condition is true.
    if (score >= 50) {
      console.log("Pass")
    }

  • else if Statement:
    Provides additional conditions if the preceding if condition is false.
    if (score >= 90) {
      console.log("A grade")
    } else if (score >= 80) {
      console.log("B grade")
    }

  • else Statement:
    Executes a code block if none of the preceding conditions are met.
    if (score >= 50) {
      console.log("Pass")
    } else {
      console.log("Fail")
    }

  • switch Statement:
    Compares an expression against multiple values and executes the matching case.
    switch (day) {
      case "Monday":
        console.log("Start of the week")
        break
      case "Friday":
        console.log("End of the week")
        break
      default:
        console.log("Midweek")
    }

2. LOOPS

  • Loops repeatedly execute a block of code as long as a specified condition holds true.
    They are useful for iterating over sequences or performing repeated actions.

  • for Loop:
    Initializes a counter, checks a condition, and iterates until the condition is false.
    for (let i = 0; i < 5; i++) {
      console.log(i)
    }

  • while Loop:
    Continues to execute as long as the condition is true.
    let i = 0
    while (i < 5) {
      console.log(i)
      i++
    }

  • do while Loop:
    Executes the block once before checking the condition and continues as long as the condition remains true.
    let i = 0
    do {
      console.log(i)
      i++
    } while (i < 5)

3. LOOP CONTROL

  • Loop control statements modify the normal execution flow within a loop.
    They provide fine control over loop iteration.

  • break:
    Immediately terminates the loop when a certain condition is met.
    for (let i = 0; i < 10; i++) {
      if (i === 5) {
        break
      }
      console.log(i)
    }

  • continue:
    Skips the rest of the current iteration and moves to the next iteration.
    for (let i = 0; i < 10; i++) {
      if (i % 2 === 0) {
        continue
      }
      console.log(i)
    }

IMPORTANT TIPS & NOTES:
  • Define clear conditions for loops to avoid infinite loops.
  • Use break and continue wisely to ensure that the code remains readable.
  • Experiment with different conditional statements and loops to build a solid understanding of control flow in JavaScript.
  • Mastery of control flow is essential for writing efficient and maintainable code.

END OF NOTES
```
