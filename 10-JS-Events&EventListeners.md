```js

Day 10: Events & Event Listeners (M)

1. EVENT LISTENERS

  • Event listeners allow your code to respond to user actions or other events on web page elements.
  • The addEventListener() method attaches a specified function to an event on a target element.
    element.addEventListener("click", function() { ... })
  • This method supports various event types, such as click, mouseover, keypress, and more.

2. EVENT BUBBLING & CAPTURING

  • Event Bubbling:
    When an event occurs on an element, it triggers first on that element and then propagates upward to its parent elements.
  • Event Capturing:
    The event begins at the root of the document and travels down to the target element before bubbling back up.
  • By specifying a boolean parameter in addEventListener(), you can choose to handle the event during the capturing phase (true) or the bubbling phase (false).

3. EVENT DELEGATION

  • Event delegation takes advantage of event bubbling by placing a single event listener on a parent element instead of on each individual child element.
  • The listener checks event.target to determine which child element triggered the event.
  • This method is efficient and particularly useful for managing events on dynamically added elements.

4. PREVENTING DEFAULT BEHAVIOR

  • Many HTML elements have default actions associated with events, such as a link navigating to a new page or a form submitting.
  • The preventDefault() method cancels the default behavior of an event.
    For instance, calling preventDefault() on a link's click event stops the browser from following the URL.
  • This is useful for implementing custom functionality without triggering the element's inherent behavior.

IMPORTANT TIPS & NOTES:
  • Ensure that event listeners are attached after the DOM has loaded to avoid targeting non-existent elements.
  • Understand the difference between event bubbling and capturing to choose the appropriate phase for your listeners.
  • Utilize event delegation to simplify event management and improve performance in applications with many similar elements.
  • Use preventDefault() carefully to override native behaviors while maintaining usability and accessibility.
  • Regular testing across different browsers is recommended to ensure consistent event handling.

END OF NOTES
```
