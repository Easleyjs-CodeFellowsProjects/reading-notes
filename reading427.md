# Reading Notes (401) Reading 27 - easleyjs

useState

## Questions
**Summarize the five steps of thinking in react.**

- Break the UI into a component hierarchy
- Build a static version in React
- Find the minimal but complete respresentation of UI state
- Identify where state should live
- Add inverse data flow


**What is one reason a local variable isn’t sufficient for managing a React component?**

Local variables don’t persist between renders.

**What is the argument to the useState hook, and what are the two parts of its return array?**

Getter and settler

**How can Component A access state from Component B?**

Lift state up to the nearest parent element
