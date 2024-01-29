1. What is NPM?
NPM stands for Node Package Manager. It is a package manager for JavaScript programming language and is widely used for managing and sharing reusable code. Developers use NPM to install, share, and manage dependencies (libraries and tools) in their projects.

2. What is SPA?
SPA stands for Single Page Application. It is a web application or website that interacts with the user by dynamically rewriting the current page, rather than loading entire new pages from the server. This provides a smoother and more fluid user experience.

3. What is the event loop?
The event loop is a crucial part of JavaScript's concurrency model. It continuously checks the message queue for new tasks and executes them in a loop. It allows JavaScript to handle asynchronous operations by utilizing callbacks and promises, ensuring that non-blocking code can run efficiently.

4. What is the difference between export x and export default x? How do you import them differently?
export x: Used to export a named variable, function, or class. When importing, you need to use the same name inside curly braces.
export default x: Used to export a default export from a module. When importing, you can choose any name for the imported item.

5. Why do you use className as a property in React and not class?
In React, the class attribute is used in JavaScript classes. To avoid confusion with JavaScript's class keyword, React uses className for applying CSS classes to elements.

6. Why should you not write the following? What will happen?
<button onClick={setCounter(counter + 1)}> +1 </button>
This code would immediately invoke setCounter(counter + 1) when rendering the component, causing the state to be updated on each render. To fix this, you should use a callback function to update the state based on the current state:

7. What is object deconstruction and how is it connected to React components (example)?
Object destructuring is a JavaScript feature that allows you to extract properties from an object and assign them to variables. In React, it's often used to destructure props directly in the function parameters.

8. How is it possible to use HTML and JavaScript in the same function (like in a React Component)? What makes it possible under the hood?
React uses JSX (JavaScript XML) syntax, which allows you to write HTML-like code in your JavaScript files. JSX gets transpiled to regular JavaScript using tools like Babel. This transformation enables developers to seamlessly integrate JavaScript logic and HTML structure within the same component.

9. What is async/await? Bring an example.
async/await is a syntax in JavaScript used with functions declared with the async keyword. It allows you to write asynchronous code in a more synchronous style, making it easier to understand.

10. What is a Promise? Bring an example.
A Promise is an object representing the eventual completion or failure of an asynchronous operation. It has states (pending, fulfilled, or rejected) and allows chaining of callbacks for handling the results.

