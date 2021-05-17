## State and Props

- Based off the diagram, the ‘render’ happens before the ‘componentDidMount’.
- The very first thing to happen in the lifecycle of React is mounting, the componentWillMount() method is the first called in this phase.
- These things will happen in this order:
   1- constructor()
   2- render()
   3- componentDidMount()
   4- React Updates
   5- componentWillUnmount()

- componentDidMount is executed after the first render only on the client side, this is where AJAX requests and DOM or state updates should occur.


- Types of things can you pass in the props can be any data type, from strings to functions, objects, etc.
- The main differance between props and state; in props you passed into a component and is handeled inside that component, but state is handeld outside that component and must be updated outside.
- We re-render our application when we change the state inside the application.
- input elements, iside forms(checkbox and others).