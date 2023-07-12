# Reading Notes 02 - easleyjs

## Overview
Continuing to learn about Components, Props, and State. Understanding how data is/should be passed between components in a React application is important because it allows us to make the right choice on how/when to pass data. Working with data inside an app is a core piece of functionality, and without it, we'd only know how to make very simple, static apps.

## Things I want to know more about
- Use cases for things that would go in the different life cycle stages.

-- Reading Questions
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render

2. What is the very first thing to happen in the lifecycle of React?

The constructor runs

3. Put the following things in the order that they happen: 
- constructor
- render
- React Updates
- componentDidMount
- componentWillUnmount

4. What does componentDidMount do?
It's invoked immediately after the component is mounted. Provides a good place to load outside data, or initialize DOM elements.

5. What types of things can you pass in the props?
Any data from outside the component that the component needs - could be values for logic, or data for display in an element.

6. What is the big difference between props and state?
Props are passed in from the parent object, state is kept inside the component itself.

7. When do we re-render our application?
Whenever the props for a component or it's state change.

8. What are some examples of things that we could store in state?
Input values from a form, or general data for use in an app


