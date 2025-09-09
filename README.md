* What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
=>
 1# getElementById finds one element with a specific ID. It always returns a single element.
2# getElementsByClassName finds all elements with a specific class. It returns a live html like array.
3# querySelector finds the first element that matches any CSS selector you give it.
4# querySelectorAll finds all elements that match a CSS selector and returns a static NodeList.
*How do you create and insert a new element into the DOM?
=> First, I create an element using document.createElement.
Then, I can add text or HTML inside it.
Finally, I will insert it into the page using appendChild, prepend, or insertBefore.

* What is Event Bubbling and how does it work?
=> Event bubbling is when an event on an element (like a click) “bubbles up” from the element to its parent, then the parent’s parent, and so on, all the way to the document.
This means a parent element can also respond to events that happen on its children.

* What is Event Delegation in JavaScript? Why is it useful?
=>Event delegation is when you attach one event listener to a parent instead of many listeners to each child. The parent then checks which child triggered the event and responds accordingly.
It’s useful because it reduces code and works even for elements added dynamically after the page loads.

* What is the difference between preventDefault() and stopPropagation() methods?
=> preventDefault() stops the browser’s default action (like following a link or submitting a form).
stopPropagation() stops the event from bubbling up to parent elements.
