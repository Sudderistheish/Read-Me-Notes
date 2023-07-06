# CReadings: Introduction to React and Components
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.
Review the Submission Instructions for guidance on completing and submitting this assignment.
Reading
Component-Based Architecture
1.	What is a “component”?
component" refers to a modular and reusable piece of software or hardware that performs a specific function within a larger system. Components can be thought of as building blocks that can be combined and interconnected to create more complex systems or applications.

2.	What are the characteristics of a component?
3.	What are the advantages of using component-based architecture?
Characteristics of components may include:
Reusability: Components can be reused in different contexts or projects, which helps in reducing development time and effort.
Encapsulation: Components encapsulate their implementation details, exposing only the necessary interfaces for interaction with other components.
Modularity: Components are self-contained and can be independently developed, tested, and maintained.
Composability: Components can be combined or composed together to build larger systems or applications.
Replaceability: Components can be easily replaced with alternative implementations as long as the interfaces remain consistent.
Advantages of using a component-based architecture include:
Reusability: Components can be reused across different projects, leading to increased productivity and reduced development time.
Maintainability: Components are modular and encapsulated, making it easier to maintain and update specific parts of a system without impacting the entire application.
Scalability: Components allow for the development of scalable systems by breaking down complex functionalities into manageable and independent units.
Collaboration: Component-based architectures promote team collaboration as developers can work on individual components independently.
Testing: Components can be tested in isolation, facilitating easier unit testing and debugging.

What is Props and How to Use it in React
1.	What is “props” short for?
2.	How are props used in React?
3.	What is the flow of props?
In React, "props" is short for "properties." It is a mechanism for passing data from a parent component to a child component. Props are essentially the inputs or configurations that can be passed to a React component.
Props are used in React by defining them as attributes on a component when it is used in JSX (JavaScript XML) syntax.
The flow of props in React is unidirectional, meaning they are passed from parent components to child components. Parent components can pass props to their child components, but child components cannot directly modify or send props back to their parent components. This ensures a predictable data flow and helps maintain the integrity of the application's state. If a child component needs to communicate with its parent or modify the data, it can do so by invoking functions passed as props from the parent component.
Class 1 Notes