1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer: The getElementById finds only one element by its unique ID, which is always returns a single element object. In contrast , The getElementsByClassName finds all the elements with the given class name, which is returns a live html collection.
On the other hand, The querySelector finds the first element that matches a CSS selector whereas The guerySelectorAll finds all elements that matches a CSS selector.

2. How do you create and insert a new element into the DOM?

Answer: We create a new element by using document.createElement(), and then insert it into the DOM with methods like appendChild(), append() etc.

3. What is Event Bubbling and how does it work?

Answer: Event bubbling is the process where an event starts from the target element and then bubbles up to its parent elements one by one, until it reaches the top document.

4. What is Event Delegation in JavaScript? Why is it useful?

Answer: Event delegation is a JavaScript technique where a single event listener is added to a parent element to handle events from its child elements using event bubbling. 
It is useful because it improves performance, works with dynamically added elements, and keeps the code clean.

5.What is the difference between preventDefault() and stopPropagation() methods?

Answer: The preventDefault() method stops the browsers default behavior Whereas the stopPropagation() method stops the event from bubbling to up.