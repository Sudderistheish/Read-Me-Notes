# Class 5 Notes 
Reading
React Docs - Thinking in React
1.	What is the single responsibility principle and how does it apply to components?
2.	What does it mean to build a ‘static’ version of your application?
3.	Once you have a static application, what do you need to add?
4.	What are the three questions you can ask to determine if something is state?
5.	How can you identify where state needs to live?
Higher-Order Functions
1.	What is a “higher-order function”?
2.	Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
3.	Explain how either map or reduce operates, with regards to higher-order functions.




Single Responsibility Principle and its application to components:
The Single Responsibility Principle (SRP) is a software design principle that states that a component or module should have only one reason to change. In the context of React components, this principle suggests that a component should ideally have a single responsibility or purpose.
Applying the SRP to React components means that each component should focus on a specific task or functionality. This helps in making components more reusable, maintainable, and testable. When a component has multiple responsibilities, it becomes harder to understand, modify, and debug.
Building a 'static' version of your application:
Building a 'static' version of an application refers to creating a representation of the user interface (UI) without any interactivity or dynamic behavior. It means constructing the UI components and their structure using static data, without incorporating any user input, state changes, or event handlers.
Adding interactivity to the static application:
Once a static version of the application is created, the next step is to add interactivity. This involves identifying the minimal set of mutable state that the UI needs and determining where this state should be stored. The static components are transformed into dynamic ones by introducing state, event handling, and updating the UI based on user input.
Three questions to determine if something is state:
To determine if something should be treated as state in React, you can ask the following questions:
1.	Is it passed in from a parent via props? If yes, it's probably not state.
2.	Does it remain unchanged over time? If yes, it's probably not state.
3.	Can you compute it based on other state or props in the component? If yes, it's not state.
Identifying where state needs to live:
To identify where state should be stored in a React application, you can follow these steps:
1.	Identify all the components that render something based on the same state.
2.	Find a common owner component (a component that encompasses all the components that need access to the state).
3.	Either the common owner component or another higher-level component should own the shared state. If multiple components need access to the same state, it is usually lifted up to their closest common ancestor.
Higher-Order Functions:
A higher-order function is a function that takes one or more functions as arguments or returns a function as its result. In other words, it is a function that operates on other functions.
Explaining line 2 of the greaterThan function:
In the greaterThan function mentioned in the reading, line 2 is creating an inner function named "test" that takes a parameter called "n". This inner function is then returned by the outer function.
In simple terms, line 2 defines a new function that compares its argument "n" with the value stored in the original function's "m" variable. The inner function "test" can access the "m" variable even after the outer function has finished executing. This is an example of a closure, where an inner function retains access to variables from its parent function's scope.
Map or reduce operations in higher-order functions:
Map and reduce are both higher-order functions commonly used with arrays.
•	Map: The map function transforms each element of an array by applying a given function to it, creating a new array with the transformed values. It takes a callback function as an argument and applies this function to each element of the array, returning a new array with the results.
•	Reduce: The reduce function iterates over an array and accumulates a single value by applying a callback function to each element. It takes a callback function and an initial value as arguments. The callback function receives two parameters: an accumulator (the accumulated value) and the current element of the array. The reduce function executes the callback for each element, updating the accumulator, and finally returns the accumulated value.
In summary, map transforms each element of an array individually, while reduce combines all elements into a single value.
