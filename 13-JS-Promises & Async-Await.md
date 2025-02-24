```js

Day 12: Promises & Async/Await (H)

Understanding Promises:
const myPromise = new Promise((resolve, reject) => {
  setTimeout(() => {
    let success = true
    if (success) {
      resolve("Operation successful!")
    } else {
      reject("Operation failed!")
    }
  }, 1000)
})

myPromise.then(result => {
  console.log(result)
}).catch(error => {
  console.error(error)
})

Chaining Promises:
myPromise
  .then(result => {
    console.log(result)
    return "Chained result"
  })
  .then(chainedResult => {
    console.log(chainedResult)
  })
  .catch(error => {
    console.error(error)
  })

Async/Await Example:
async function fetchData() {
  try {
    const result = await myPromise
    console.log(result)
  } catch (error) {
    console.error(error)
  }
}
fetchData()

Error Handling with try...catch:
async function getData() {
  try {
    const data = await myPromise
    console.log(data)
  } catch (error) {
    console.error("Error:", error)
  }
}
getData()

IMPORTANT TIPS & NOTES:
Promises represent asynchronous operations with states: pending, fulfilled, or rejected.
Chaining promises allows sequential handling of asynchronous tasks.
Async functions return a promise and let you use await for a synchronous coding style.
Always use try...catch inside async functions to handle errors gracefully.
END OF NOTES
```
