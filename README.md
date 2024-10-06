# Custom JSX Implementation

This project demonstrates a lightweight, custom implementation of JSX without using React or any other framework. It showcases how to create a simple virtual DOM and render it to the real DOM using plain JavaScript.

## Key Features

1. Custom JSX transpilation
2. Virtual DOM creation
3. Rendering virtual DOM to real DOM
4. Simple component-like functionality

## How It Works

### JSX Transpilation

The code uses a custom JSX transpilation approach, indicated by the comment:

```javascript
/** @jsx h */
```

This tells the transpiler to use the h() function for creating virtual DOM nodes.

## Virtual DOM Creation
The h() function is responsible for creating virtual DOM nodes (VNodes) from JSX syntax. Each VNode is a simple JavaScript object with properties like nodeName, attributes, and children.

## Rendering
The render() function converts the virtual DOM into real DOM elements. It recursively creates DOM nodes and sets their attributes and children.

## Component-like Functionality
The foo() function demonstrates a simple component-like approach, mapping an array of items to a list of <li> elements using JSX syntax.

## Usage
The code creates a simple virtual DOM structure, renders it to the real DOM, and appends it to the document body. It also stringifies the virtual DOM to JSON and displays it on the page.

## Example Output
The code will generate:

1. A div with an id "foo" containing:
  - A paragraph with text
  - An unordered list of fruits (apple, mango, banana)

2. A pre-formatted text block showing the JSON representation of the virtual DOM
   
## Conclusion
This implementation provides a minimalistic approach to using JSX-like syntax without the need for a full framework. It's useful for understanding the basics of how JSX and virtual DOM rendering work under the hood.

This README provides an overview of the custom JSX implementation in index.js, explaining its key features, how it works, and what it outputs. It should help users understand the purpose and functionality of the code.

