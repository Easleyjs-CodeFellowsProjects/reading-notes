# Reading Notes (401) Reading 35 - easleyjs

Redux

## Questions
**What is the first principle of Redux?**

The single immutable state tree

**what is a store and what do we use our reducers for within that store?**

The overall state where data is held for the application.

**Name three Redux store methods given to us by createStore and describe their use.**

getState() - Returns the current state
dispatch() - Sends an action to the reducer
subscribe() - creates a listener for state changes

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**

It allows you to consolidate multiple reducers that might manage multiple states into one place.
