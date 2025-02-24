```js

Day 13: Fetch API & AJAX (M)

Making API Calls:
fetch('https://api.example.com/data')
  .then(response => response.json())
  .then(data => {
    console.log(data)
  })
  .catch(error => {
    console.error(error)
  })

Handling JSON:
const jsonString = JSON.stringify({ name: "Alice", age: 30 })
const parsedData = JSON.parse(jsonString)
console.log(parsedData)

Error Handling in API Calls:
fetch('https://api.example.com/data')
  .then(response => {
    if (!response.ok) {
      throw new Error('Network response was not ok')
    }
    return response.json()
  })
  .then(data => {
    console.log(data)
  })
  .catch(error => {
    console.error('Fetch error:', error)
  })

IMPORTANT TIPS & NOTES:
Use fetch to make API calls and process responses with .then() and .catch(). Convert responses to JSON with response.json() and use JSON.stringify() and JSON.parse() to handle JSON data. Always check response.ok to catch network errors.
END OF NOTES
```
