# Reading Notes (401) Reading 41 - easleyjs

React Native and Expo

## Questions
**Name three Core Components of React Native and describe what they do.**

View - A container that supports layout, style, touch handling and accessibility controls

Text - Display text similar to a p tag

TextInput - Allows user to input text

**What problem does React Native solve (why call it native)?**

Allows us to tap into native features of the phone OS without having to write the normal compiled code for that OS

**What are the building blocks of a React Native app? How does that compare to a React app?**

Core Components, Native Components. In a React app, there wouldn't really be as many provided components - instead you would work with hooks and functionality within React.

**What solution does expo provide?**

Provides an easier way to build React Native apps

**Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.**

Managed

**What is the difference between React Native and Expo?**

React Native is a minimal set of tools to create apps which can run on mobile, and allow you to insert native mobile OS code. Expo is sort of a wrapper toolkit that provides some components and tools to create apps.

**Checkout this tool. What does snack allow you to do?**

Snack allows you to develop Expo apps in the browser

**What does “eject” mean within the context of Expo?**

Switching workflows to the Bare workflow, exposing more configuration options

**When should you not eject?**

If you do not need to customize your app beyond standard Expo options

**Why might you choose to eject?**

If you need to use native code in your project
