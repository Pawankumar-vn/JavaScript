```js

Day 9: DOM Manipulation (M)

1. INTRODUCTION TO THE DOM

  • The Document Object Model (DOM) is a tree-like representation of a web page's structure.
  • It provides a programming interface that allows JavaScript to interact with, modify, and update the content, structure, and styling of a webpage in real time.

2. SELECTING ELEMENTS

  • To manipulate the DOM, you first need to select the elements you want to work with.

  • Methods for selecting elements include:
    - getElementById(): Selects a single element by its unique ID.
    - querySelector(): Selects the first element that matches a given CSS selector.
    - querySelectorAll(): Selects all elements that match a given CSS selector and returns a NodeList.

  • Additional selection methods:
    - getElementsByClassName() and getElementsByTagName() can also be used for specific use cases.

3. MODIFYING CONTENT

  • Once elements are selected, you can change their content using properties:

  • innerText: Updates the visible text content of an element.
  • textContent: Similar to innerText, but includes all text within an element (including hidden elements) and is generally faster.
  • innerHTML: Modifies the HTML markup inside an element, allowing you to insert HTML tags as well as text.

  • Choose the property based on whether you need to manipulate plain text or HTML structure.

4. CHANGING STYLES

  • Directly alter an element's appearance by modifying its style property.

  • For example, setting element.style.backgroundColor to "blue" changes the element's background.
  • For more maintainable styling, consider using the classList API:
    - classList.add(), classList.remove(), and classList.toggle() allow you to add or remove CSS classes dynamically.

5. ADDING & REMOVING ELEMENTS

  • To dynamically modify the document structure, you can add or remove elements.

  • Adding Elements:
    - Use document.createElement() to create a new element.
    - Use appendChild() to add the new element as a child to an existing parent element.

  • Removing Elements:
    - Use removeChild() on the parent element to remove a specified child.

  • These methods are essential for building dynamic interfaces that respond to user interactions.

6. EVENT HANDLING (ADDITIONAL TOPIC)

  • DOM manipulation is often combined with event handling to create interactive web pages.

  • Attach events using addEventListener(), which lets you run a function in response to events like clicks, hovers, or key presses.
    - For example, element.addEventListener("click", function() { ... }) triggers code when the element is clicked.

7. TRAVERSING THE DOM (ADDITIONAL TOPIC)

  • Navigate the DOM tree to access related elements using properties such as:
    - parentNode, childNodes, firstChild, lastChild, nextSibling, and previousSibling.

  • This is useful when you need to manipulate elements relative to the one you have selected.

8. PRACTICAL EXAMPLES

  • Build a dynamic list where items are added or removed based on user input.
  • Create interactive components that change style or content when clicked.
  • Combine element selection, content modification, and event handling to develop mini applications like a to-do list or image gallery.

IMPORTANT TIPS & NOTES:
  • Begin by accurately selecting the element(s) you wish to manipulate to ensure your changes affect the correct parts of the DOM.
  • Understand the differences between innerText, textContent, and innerHTML to choose the most appropriate one for your needs.
  • Utilize CSS classes and the classList API for cleaner, more maintainable style modifications.
  • Practice traversing the DOM to effectively locate and manipulate related elements.
  • Test your DOM manipulation code regularly using the browser’s developer tools to debug and improve your approach.

END OF NOTES
```
