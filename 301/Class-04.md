# Read: Class 04

Proficiency in ternary operators is crucial for clean and concise code in web development, especially in frameworks like React. It enhances readability and showcases a deeper understanding of JavaScript syntax, contributing to efficient coding practices relevant to the current module.

[How to use Forms in React](https://www.robinwieruch.de/react-form/)

1. What is a ‘Controlled Component’?

In web development, a `controlled component` in React refers to a form element whose value is linked to the component's state. The component manages and updates the input value, providing full control over its behavior. This is achieved by connecting the input value directly to the component's state, ensuring synchronization between user input and component state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Update state as users enter for real-time feedback, dynamic UI updates, and progress tracking. Wait until submission for atomic updates, improved performance, and maintaining consistency. Consider a combination based on validation needs and user expectations.

3. How do we target what the user is entering if we have an event handler on an input field?

In the event handler of an input field, access the user's input using event.target.value. Update state or perform actions based on this input.

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?

Use a ternary operator for concise, one-line conditional assignments or actions based on a simple condition. It enhances readability and is a stylistic choice for some developers.

2. Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

console.log(x === y ? true : false);