#  Q.1 What is React?

# React: Building Efficient UIs with Virtual DOM and Declarative Syntax

**React** is a powerful JavaScript library designed for building dynamic and interactive user interfaces (UIs) in web and mobile applications. It stands out for its focus on:

* **Virtual DOM**
* **Declarative Programming**

## Virtual DOM

- React doesn't directly manipulate the browser's DOM (Document Object Model), which can be performance-intensive.
- Instead, it employs a **virtual DOM**, a lightweight in-memory representation of the UI.
- When the application's state changes, React efficiently updates the virtual DOM and then calculates the minimal changes needed to the actual DOM.
- This approach leads to:
    - **Faster performance**
    - **Smoother user experiences**
    - **Reduced memory usage**


# Q.2 Who made React?

* **Jordan Walke**


# Q.3 What is Babel?

## Babel as a JavaScript Compiler

In web development, Babel stands out as a powerful JavaScript compiler that bridges the gap between modern JavaScript and older browsers.

# Q.4 How does Babel convert html code in React into valid code?

# Babel and JSX in React: A Translation Story

Babel's primary role in React isn't directly converting HTML, but rather transpiling JSX, a syntax extension that resembles HTML within JavaScript code.

Here's the breakdown:

- **JSX: Not Quite HTML**
- **It's a way to write HTML-like structures within JavaScript for better readability and UI visualization.**
- **Browsers can't understand JSX directly, so it needs translation.**

- **Babel: The JSX Translator**
- **Babel steps in to convert JSX into valid JavaScript function calls.**
- **It transforms JSX elements into React.createElement() calls, essential for React's virtual DOM.**

# Q.5 What is ReactDOM used for? Write an example?

ReactDOM: The Painter of React
Imagine your React components as vibrant blueprints for your UI. To breathe life into these designs and paint them onto the web canvas, you need ReactDOM. This essential package serves as the bridge between React's virtual DOM and the browser's actual DOM, seamlessly translating blueprints into real, interactive elements on the screen.

# Q.6 What are the packages that you need to import for react to work with?

**React**
**Reactdom**

# Q.7 How do you add react to a web application?
- Setup: Get Node.js & npm.
- Project: Create a directory.
- Create App: Use npx create-react-app (easy) or install React/ReactDOM & manage build tools manually.
- Components: Write them in .jsx files.
- Render: Use ReactDOM to display your components in HTML.
- Develop: npm start (if using Create React App).
- Deploy: Build an optimized production bundle.


# Q.8 What is React.createElement?
# Q.9 What are the three properties that createElement accept?

Takes three arguments:
The type of element to create (like a div, a heading, or a custom component).
Props (properties) to pass to the element, controlling its appearance and behavior.
Children (optional nested elements or content).


# Q.10 What is the meaning of render and root?
**Function:** Refers to the render method within a React component. This method defines what appears on the screen for that specific component.
**Purpose:** Takes the component's state and props as input and returns JSX describing the UI elements to be displayed.
**Output:** The returned JSX code is used by React to update the virtual DOM and ultimately the browser's DOM, reflecting the component's current state.