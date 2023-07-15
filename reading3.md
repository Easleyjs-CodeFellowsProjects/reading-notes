# Reading Notes 03 - easleyjs

## Overview
We went over how to pass functions to prop, as well as lifting up state, and where to put state

## Things I want to know more about
- Solutions to avoid prop drilling/more advanced state management

-- Reading Questions
1. **What does .map() return?**

An array

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**

array.map(item => { return item })

3. **Each list item needs a unique ____** 

Key

4. **What is the purpose of a key?**

To identify the individual items being rendered from the array

6. **What is the spread operator?**

Turns an array into separate values

7. **List 4 things that the spread operator can do**

Merge two arrays, using an array to provide multiple arguments, making updates to React state by copying the old state, combine objects

8. **Give an example of using the spread operator to combine two arrays**

let someArray = [1,2,3,...otherArray]

9. **Give an example of using the spread operator to add a new item to an array.**

someArray.push(...otherArray)

10. **Give an example of using the spread operator to combine two objects into one.**

let someObj = { property: 'a property', ...anotherObj }

11. **In the video, what is the first step that the developer does to pass functions between components?**

Create the function you want to pass in the same class as the state

12. **In your own words, what does the increment function do?**

Searches through the people property of state, and if the name matches the parameter name, it modifies the count property for that person in state

13. **How can you pass a method from a parent component into a child component?**

As a prop, by this.function_name

14. **How does the child component invoke a method that was passed to it from a parent component?**

With this.props.function_name
