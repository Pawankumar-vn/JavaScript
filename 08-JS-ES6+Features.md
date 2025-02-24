```js

Day 8: ES6+ Features (M)

1. Destructuring
   // Array Destructuring
   const arr = [1, 2, 3];
   const [a, b, c] = arr;

   // Object Destructuring
   const obj = { x: 10, y: 20 };
   const { x, y } = obj;

2. Template Strings
   const name = "Alice";
   console.log(`Hello, ${name}!`);

3. Default Parameters
   function greet(name = "Guest") {
     return `Hi, ${name}!`;
   }

4. Spread & Rest Operators
   // Spread: Copy/Merge arrays
   const nums1 = [1, 2, 3];
   const nums2 = [4, 5];
   const allNums = [...nums1, ...nums2];

   // Rest: Collect arguments into an array
   function sum(...numbers) {
     return numbers.reduce((total, n) => total + n, 0);
   }

IMPORTANT: Use these ES6 features to write cleaner, concise code.
END OF NOTES
```
