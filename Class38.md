## Q1 How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?
in react we used to send data from base class to child using props here in next we have different techique allows us to pass data from child component to parent component called Lifting State Up . By using this why we keep our data centrlized on the parent component and easer to transmit data.

## Q2 Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.
its about rendering data or component on my app based on a condition or value state which allows us to contol vieing our data dynamilcally.
Ex:import React, { useState } from 'react';

function ExampleComponent() {
  const [showContent, setShowContent] = useState(true);

  const toggleContent = () => {
    setShowContent((prevShowContent) => !prevShowContent);
  };

  return (
    <>
      <button onClick={toggleContent}>Toggle Content</button>
      {showContent ? <p>This content is visible!</p> : <p>This content is hidden!</p>}
    </>
  );
}

## Q3:Thinking in React - Main Principles:
"Thinking in React" is an approach to designing and building React applications that emphasizes component-based thinking and a clear separation of concerns. The main principles behind it are:

a. Single Responsibility Principle: Each component should have a single responsibility, meaning it should be focused on doing one thing well. This makes components reusable, maintainable, and easier to understand.

b. Component Hierarchy: Break down the UI into a component hierarchy. Components should be structured in a tree-like manner, where parent components encapsulate their child components.

c. Data Flow: Lift the state up to a higher-level parent component when multiple components need access to the same data. Data should flow down from parent to child components through props.
Reusability: Aim to create reusable components that can be used in different parts of the application. This promotes code efficiency and reduces redundancy.

e. Single Source of Truth: Keep the application's state in a single source of truth, typically in a top-level state management system like React's Context or Redux. This ensures consistency and simplifies state management.
