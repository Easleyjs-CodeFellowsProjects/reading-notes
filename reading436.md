# Reading Notes (401) Reading 36 - easleyjs

Redux - combineReducers

## Questions
**Why create multiple reducers?**

To break the state out into different functional areas

**How would you combine multiple reducers?**

You can create them in separate files and bring them in and combine them with combineReducers

**How will you manage state as an immutable object? why?**

You never modify it directly. You make a copy and add your variables on top of that.

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**

Redux reducers

**Explain how combineReducers assembles the new state tree.**

It takes an object full of slice reducer functions and returns a new reducer function

**How would you define initial state in an app using combineReducers?**

Set up reducers. Use combineReducers. Use createStore.

**Why will you want to split your reducing functions as your app becomes more complex?**

So that it's easier to manage specific parts of the state.

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**

CombineReducers. CreateStore.

**What is a popular convention when naming reducers?**

Naming them after the slice they'll be managing.
