# Reading Notes (401) Reading 32 - easleyjs

Context and Reducer combined.

## Questions
**How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)**

By themselves, useReducer and useContext are both ways to reduce redundancy in a React app. useReducer minimizes the number of required "states"/useState instances. useContext reduces the number of props that are needed to be passed down. Both tend to be most effective in situations where you have more than one state or props to manage, respectively.

Used together, they can manage a complex state which is used in various components in an app. This could be complex app data, or something like a complex theme for an app. By coupling the two hooks together, we can create a state with various different updateable elements that can be passed to various components without prop drilling.
