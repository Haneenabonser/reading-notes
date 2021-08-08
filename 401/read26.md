## Component Based UI

### Review, Research, and Discussion
- Name 5 Javascript UI Frameworks (other than React)
    - Angular
    - Vue.js
    - jQuery
    - Polymer
    - Backbone.js
- What’s the difference between a framework and a library?
    - The major difference between frameworks and libraries is complexity. Libraries offer fewer complexities, and frameworks are the opposite. A library is a collection of packages that performs specific operations. On the other hand, frameworks contain the basic flow and architecture of the application.

### Document the following Vocabulary Terms
- Rendering: refers to showing the output in the browser, in React; rendering is a process that is triggered by a change of state in some component of your application, when a state change occurs React: It will collect from the root of your App all the components that requested a re-render because their state or their props changed.
- Templates: refer to a sample fill-in-the-blank document that can help in saving time. Usually templates are customized documents that may have sample content, themes, etc.
- State: is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

### Preparation Materials
- Introducing JSX
> Why JSX?

    - React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.
    - Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.
    - React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

- Rendering Elements
> \<div id="root"\>\</div\>

    - We call this a “root” DOM node because everything inside it will be managed by React DOM. Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

    - To render a React element into a root DOM node, pass both to ReactDOM.render():