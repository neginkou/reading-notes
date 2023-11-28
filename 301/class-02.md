# Read: Class 02

The topics mentioned, such as storing form data, managing UI state, tracking numeric values, and handling loading status, directly impact the way a React application responds to user interactions. By mastering these concepts, you gain the ability to create interactive and efficient user experiences.

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

The component is created with the `constructor`. The component `renders` for the first time. `componentDidMount`: This method is called after the component has been rendered for the first time.

2. What is the very first thing to happen in the lifecycle of React?

In the React component lifecycle, the very first thing that happens is the `initialization` of the component. This involves the creation of the component and the execution of its constructor method, if one is defined. The constructor is where you typically set the initial state and bind event handlers.

## Things I want to know more about

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.

`constructor` -> `render` -> `componentDidMount` -> `React Updates` (if any, including `shouldComponentUpdate`, `render`, `componentDidUpdate`) -> `componentWillUnmount`.

4.What does `componentDidMount` do?

`componentDidMount` is a React lifecycle method called after a component is first rendered. It's commonly used for tasks like fetching data from an API, setting up subscriptions, or interacting with the DOM. It executes once during the component's lifecycle.

[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. Primitive Data Types:
* Strings, Numbers, Booleans

2. Functions:
* Enable communication between components.

3. Objects:
* Complex data structures.

4. Arrays:
* Lists of items.

5. React Elements:
* Allowing component composition.

6. Callback Functions:
* Communicate changes from child to parent components.


2. What is the big difference between props and state?

Props:

* Immutable data passed from parent to child.
* Read-only, controlled by parent.
* Used for communication between components.

State:

* Mutable data managed internally by a component.
* Can be modified using `setState`.
* Used for managing and representing the component's own state.

3. When do we re-render our application?

 A re-render in a React application occurs when:

* The component's state changes using `setState`.
* The component receives new props from its parent.
* `forceUpdate` is explicitly called.
* A parent component re-renders, causing its child components to re-render as well.

4. What are some examples of things that we could store in state?

* Form data (input values, checkboxes).
* UI state (modals, tooltips).
* Numeric values (counters).
* Loading/fetching status.
* Selected items in a list.
* Authentication status.
* Toggle state for visibility/behavior control.