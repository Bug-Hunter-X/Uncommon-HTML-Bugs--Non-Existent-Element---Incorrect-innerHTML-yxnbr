This repository demonstrates two uncommon HTML errors:

1. **Accessing a non-existent element:**  Trying to manipulate an element that hasn't been parsed or rendered by the browser will lead to an error.  This often happens when scripts run before the DOM is fully loaded.
2. **Incorrect `innerHTML` usage:** Using `innerHTML` to set a numerical value is generally bad practice. While it may appear to work, it's less efficient and can cause unexpected issues compared to using `textContent` for numbers.