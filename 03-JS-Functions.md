```js
Day 3: Functions (E)

1. FUNCTION FUNDAMENTALS

  • Functions are reusable blocks of code designed to perform specific tasks.
    They help encapsulate logic, promote code reuse, and improve maintainability.

2. DECLARATIONS VS. EXPRESSIONS

  • Function Declarations:
    Define a function using the function keyword followed by a name and a parameter list.
    They are hoisted, which means they can be called before their definition in the code.

  • Function Expressions:
    Define a function as part of a variable assignment.
    They are not hoisted in the same way as declarations, so they must be defined before being invoked.

3. ARROW FUNCTIONS (=>)

  • Arrow functions provide a concise syntax for writing functions.
    They allow for implicit returns when a single expression is used.

  • Differences from Traditional Functions:
    Arrow functions do not have their own this binding; instead, they inherit this from the surrounding lexical scope.
    This behavior is beneficial in contexts where maintaining the correct this value is crucial.

4. IMMEDIATELY INVOKED FUNCTION EXPRESSIONS (IIFE)

  • An IIFE is a function that is defined and executed immediately.
    This pattern creates a private scope, which helps avoid polluting the global namespace and keeps variables local.

5. PARAMETERS & ARGUMENTS

  • Passing Data:
    Parameters are the named variables listed in a function's definition.
    Arguments are the actual values provided to the function when it is called.

  • Default Parameters:
    Functions can define default values for parameters, ensuring that a fallback value is used when no argument is provided.

  • Rest Parameters:
    The ...args syntax allows a function to accept a variable number of arguments, which are gathered into an array.

6. RETURN STATEMENTS & SIDE EFFECTS

  • Returning Values:
    Functions compute and return a value using the return statement.
    The returned value can be stored or used directly in further computations.

  • Pure Functions vs. Functions with Side Effects:
    Pure functions always return the same output for the same input and do not modify external state.
    Functions with side effects interact with or alter variables outside their own scope, which can lead to unpredictable behavior.

7. SCOPE & CONTEXT

  • Local vs. Global Scope:
    Variables declared within a function are local and accessible only inside that function.
    Global variables are declared outside of functions and can be accessed throughout the entire codebase, which requires careful management to avoid conflicts.

  • Introduction to Closures:
    A closure occurs when a function retains access to its outer scope even after that outer function has finished executing.
    This concept is key to creating private variables and functions, as well as implementing advanced design patterns.

IMPORTANT TIPS & NOTES:
  • Understanding function fundamentals is critical for building modular, efficient, and maintainable JavaScript code.
  • Choose function declarations or expressions based on the context and the need for hoisting or lexical this binding.
  • Use arrow functions for shorter syntax and when the surrounding this context should be preserved.
  • Leverage IIFEs to encapsulate code and avoid global namespace pollution.
  • Clarify the difference between parameters and arguments to ensure proper data handling in functions.
  • Recognize the impact of side effects and strive for pure functions when predictability and testability are required.
  • Master closures to create powerful abstractions and manage scope effectively.

END OF NOTES

```
