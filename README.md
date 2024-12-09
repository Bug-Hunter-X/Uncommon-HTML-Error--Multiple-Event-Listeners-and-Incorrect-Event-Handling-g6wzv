# Uncommon HTML Error: Multiple Event Listeners and Incorrect Event Handling

This repository demonstrates some uncommon errors that can occur when working with event listeners in HTML.  These errors can lead to unexpected behavior and difficult-to-debug issues.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file shows the corrected code.

**Error 1:** Multiple Event Listeners attached to the same element. This could lead to unwanted repetitive function calls.
**Error 2:** Mixing different types of event listeners.  The event listener should be attached correctly using addEventListener or directly attaching a function to the element.
**Error 3:** Incorrect way of adding an event listener. Event Listener can be attached using addEventListener and by setting the property of an element.