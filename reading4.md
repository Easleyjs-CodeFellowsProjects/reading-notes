# Reading Notes 04 - easleyjs

## Overview
We learned about forms, and capturing input events.

## Things I want to know more about
- One-way binding. Is this referring to things being bound to state but not the other way around?

-- Reading Questions
1. **What is a ‘Controlled Component’?**

A component whose state/values are controlled by a higher-level parent state.

2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

We should wait until they're done updating the form, since they might make changes/corrections before they're done.

3. **How do we target what the user is entering if we have an event handler on an input field?** 

event.target.value

4. **Why would we use a ternary operator?**

To make our code shorter and more readable.

6. **Rewrite the following statement using a ternary statement:**

x===y ? true : false
