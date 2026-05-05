1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll ?
Answer : getElementById --> returns single element by ID.
         getElementsByClassName --> returns multiple elements by class Name.
         querySelector --> returns first matching element by css selector.

2. How do you create and insert a new element into the DOM?
Answer : create a new element with document.createElement() and insert a new element     with appendChild().


3. What is Event Bubbling? And how does it work?
   Answer : Event Bubbling is when click on a child element bubbles up and and triggers the click events all of its parent elements.

4. What is Event Delegation in JavaScript? Why is it useful?
   Answer: Event delegation means using a parent element to handle events of its child elements, and it is useful because it improves performance and works for dynamically added elements.


5. What is the difference between preventDefault() and stopPropagation() methods?
   Answer: preventDefault() stops the browser default action andstopPropagation stops the event from bubbling up to parent elements.