```js

Day 4: Arrays (M)

1. CREATING ARRAYS

  • Arrays are used to store multiple values in a single variable.
    They are created using square brackets [] and can contain elements of any data type.
    let fruits = ["apple", "banana", "cherry"]

2. ESSENTIAL ARRAY METHODS

  • Mutating Methods:
    • push() adds one or more elements to the end of an array.
    • pop() removes the last element from an array.
    • shift() removes the first element from an array.
    • unshift() adds one or more elements to the beginning of an array.
    • splice() can add, remove, or replace elements at a specified index within an array.
    • reverse() changes the order of the array’s elements by reversing them.
    • sort() arranges the elements based on their Unicode code points or by a provided comparison function.

  • Non-Mutating Methods:
    • slice() returns a new array containing a portion of the original array without altering it.
    • concat() merges two or more arrays into a new array.
    • join() combines all elements of an array into a single string, using an optional separator.

3. ITERATING OVER ARRAYS (forEach, map, filter, reduce)

  • forEach executes a provided function once for each array element.
    fruits.forEach(item => console.log(item))

  • map creates a new array populated with the results of calling a function on every element.
    let upperFruits = fruits.map(item => item.toUpperCase())

  • filter creates a new array with all elements that pass a test implemented by a function.
    let longNamedFruits = fruits.filter(item => item.length > 5)

  • reduce executes a reducer function on each element of the array, resulting in a single output value.
    let concatenatedFruits = fruits.reduce((acc, item) => acc + ", " + item)

4. SPREAD (...) AND REST PARAMETERS

  • The spread operator (...) expands an array into individual elements.
    let moreFruits = ["kiwi", "pineapple"]
    let allFruits = [...fruits, ...moreFruits]

  • Rest parameters collect multiple elements into a single array within a function parameter.
    function displayFruits(...items) {
      console.log(items)
    }
    displayFruits("apple", "banana", "cherry")

IMPORTANT TIPS & NOTES:
  • Arrays are fundamental for managing collections of data in JavaScript.
  • Master common array methods to efficiently add, remove, and manipulate data.
  • Practice iterating over arrays using forEach, map, filter, and reduce to handle data transformations.
  • Understand the difference between the spread operator and rest parameters; one expands arrays while the other collects arguments.
  • Experiment with combining these methods to build robust data manipulation functions.

END OF NOTES
```
