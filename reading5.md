# Reading Notes 05 - easleyjs

## Overview
We learned about forms, and capturing input events.

## Things I want to know more about
- One-way binding. Is this referring to things being bound to state but not the other way around?

-- Reading Questions
1. **What is the single responsibility principle and how does it apply to components?**

A function or component should only have one purpose/function.

2. **What does it mean to build a ‘static’ version of your application?**

To have a version of the application that doesn't require state/interactivity, and components just take data from props.

3. **Once you have a static application, what do you need to add?** 

Interactivity/state to components where necessary.

4. **What are the three questions you can ask to determine if something is state?**

Does it remain unchanged over time, is it passed from parent to child via props, can you compute it based on state or props?

6. **How can you identify where state needs to live?**

I should live in the uppermost component where it's interacted with.

7. **What is a “higher-order function”?**

A function that operates on other functions.

8. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

Returns a function that multiples it's parameter by the original parameter passed to greaterThan.

10. **Explain how either map or reduce operates, with regards to higher-order functions**

Map runs a function on the array passed to it, which could be an array of functions.
