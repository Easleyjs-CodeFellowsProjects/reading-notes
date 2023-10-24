# Reading Notes (401) Reading 19 - easleyjs

React Components

## Questions
**What are the building blocks of a React app?**

Components

**What is the difference between an HTML element and a React component?**

React components are rendered by React, can have logic, and start with a capital letter.

**What is JSX and why do we use it?**

It encapsulates HTML, JS, and React functionality.

**Describe the process of embedding JavaScript expressions in JSX.**

Place your code inside curly braces

**Does React or JSX have any special features for iteration or conditional logic?**

Nope, you just use if/else.

**How does React know to respond to a user’s inputs?**

By using event handlers.

**What word indicates that a React component manages data with a Hook?**

use

**How can two react components share data?**

Move state updwards to the closest parent component.

**What are the three steps of refreshing a React UI?**

Trigger - Render - Commit

**How do you trigger updates to a component after the initial render?**

Change its state

**Does React recreate DOM nodes on every rerender?**

No, it only updates the nodes that have changed

**After React has updated the DOM, what still needs to happen before the user sees the change?**

It needs to be rendered and committed

