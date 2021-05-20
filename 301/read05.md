## Putting it all together 

**React Docs - thinking in React**

- How would you break a mock into a component heirarchy?
    - Draw boxes around every component and giv them all names.
- What is the single responsibility principle and how does it apply to components?
    - Meaning a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents, HOW? using the UI in tha JSON file and Separate the UI into components, where each component matches one piece of the data model.


- What does it mean to build a ‘static’ version of your application?
    - Have a library of reusable components that render our data model, it requires a lot of typing and no thinking, we can do it using props to pass data and never use states.
- Once you have a static application, what do you need to add?
    - Use states to make the UI interactive, key to do this is DRY.
- What are the three questions you can ask to determine if something is state?
    - it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.
- How can you identify where state needs to live?
    - Identify every component that renders something based on that state.
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).
    - Either the common owner or another component higher up in the hierarchy should own the state.
    - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


## Things I want to know more about