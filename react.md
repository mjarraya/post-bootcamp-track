# React

## Hooks

[Video Introduction (and official docs)](https://reactjs.org/docs/hooks-intro.html#video-introduction)  

## Context

Per the [docs](https://reactjs.org/docs/context.html), *Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.*

Still per the docs, *Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, [component composition](https://reactjs.org/docs/composition-vs-inheritance.html) is often a simpler solution than context.* (see [Using Composition to avoid Prop Drilling](https://www.youtube.com/watch?v=3XaXKiXtNjw))  

## Styling

### CSS Modules

[What are CSS Modules and why do we need them](https://css-tricks.com/css-modules-part-1-need/)  
[Understanding the CSS Modules Methodology](https://www.sitepoint.com/understanding-css-modules-methodology/)  

### styled components

[styled-components.com](https://styled-components.com/)  

## PropTypes

React allows you to check the types of a component's props (to mitigate bugs) with [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html).  

## Code Splitting

Code Splitting can improve performance by reducing the amount of non-used code being loaded by our app.  

[docs](https://reactjs.org/docs/code-splitting.html)  

## State management libraries

In more complex applications, organizing the state can quickly become a challenge.  

### Redux

Redux is based on the [Flux architectural pattern](https://code-cartoons.com/a-cartoon-guide-to-flux-6157355ab207) and aims to bring a single store -an immutable state-  for the data that all components in our application rely on and update.  

[reduxjs.org](https://redux.js.org/)
[A Cartoon intro to Redux](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)  
[Adding Redux to a Simple React App](https://www.youtube.com/watch?v=sX3KeP7v7Kg&t=9s)  

### MobX

MobX offer a different approach, more object-oriented than Redux's functional approach, with multiple stores and a mutable state.

[Mobx.js.org](https://mobx.js.org/README.html)  
[Redux vs MobX](https://www.robinwieruch.de/redux-mobx)  

## Testing

[Reactjs.org docs](https://reactjs.org/docs/testing.html)  
[common testing patterns](https://reactjs.org/docs/testing-recipes.html)  
[snapshot testing with Jest](https://jestjs.io/docs/en/tutorial-react)  
[How to test React with Jest and Enzyme](https://www.robinwieruch.de/react-testing-jest-enzyme)  
