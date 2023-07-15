 #Class 4 Notes 
 Reading
React Docs - Forms
1.	What is a ‘Controlled Component’?
 An input form element whose value is controlled by React in this way is called a “controlled component”.
This means that the value of the input field is not directly managed by the DOM, but rather by React state. Whenever the user interacts with the input field, React updates the state, and the value of the input field reflects the state value. This approach allows React to have full control over the input's value and enables synchronization between the state and the UI.

2.	Should we wait to store the user’s responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
In general, it's a good practice to update the state with the user's responses as soon as they enter them rather than waiting for the form submission. By updating the state immediately, you can provide real-time feedback to the user, perform validation checks, and respond to changes dynamically. It also allows you to utilize the entered values for any calculations or manipulations that might be required before the form submission. Waiting until the form submission can lead to a less interactive and responsive user experience.
3.	How do we target what the user is entering if we have an event handler on an input field?
To target what the user is entering when you have an event handler on an input field, you can access the entered value through the event object. In React, the event object is typically named e or event and is passed as an argument to the event handler function. You can retrieve the entered value using the event.target.value property. 

The Conditional (Ternary) Operator Explained
1.	Why would we use a ternary operator? The ternary operator is used as a shorthand for conditional expressions. It provides a concise way to write conditional statements in a single line. The ternary operator takes three operands: a condition, a value to be returned if the condition is true, and a value to be returned if the condition is false. It's often used when you need to assign a value or execute a statement based on a condition.

2.	Rewrite the following statement using a ternary statement:
consle.log(x ===y ? true : false);

3.	if(x===y){
4.	  console.log(true);
5.	} else {
6.	  console.log(false);
7.	}
Bookmark and Review
In this ternary expression, the condition x === y is checked. If the condition is true, the value true is returned, and it is logged to the console. If the condition is false, the value false is returned and logged to the console. The ternary operator condenses the if-else statement into a single line of code.


•	React Bootstrap - Forms
•	React Docs - conditional rendering
