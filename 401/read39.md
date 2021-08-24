## Redux - Additional Topics

### Review, Research, and Discussion
- What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
    - to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.
    - Create an empty object or array to the initial state, dispatch the action in useEffect hook.

- When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
    - the thunk action, because it is the one that will be used in the components

### Document the following Vocabulary Terms
- middleware: is software which lies between an operating system and the applications running on it. 
- thunk: is a middleware that allows you to call the action creators that return a function(thunk) which takes the store's dispatch method as the argument and which is afterwards used to dispatch the synchronous action after the API or side effects has been finished.

### Preparation Materials
***Redux Toolkit (RTK)***
    - RTK Query is an optional addon included in the Redux Toolkit package, and its functionality is built on top of the other APIs in Redux Toolkit.
    - RTK Query is a powerful data fetching and caching tool. It is designed to simplify common cases for loading data in a web application, eliminating the need to hand-write data fetching & caching logic yourself.
