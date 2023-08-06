# Reading Notes 09 - easleyjs

## Overview
Functional Programming and Modules

## Things I want to know more about
When are important times to use Functional Programming in JS?

-- Reading Questions
**What is functional programming?**

A style of building computer programs that deals with functions and avoids changing state or mutating data.

**What is a pure function and how do we know if something is a pure function?**

A function that is predictable and doesn't have side effects. It has to meet those two criteria.

**What are the benefits of a pure function?**

Always returns the same value if given the same input. Does not have side effects.

**What is immutability?**

An object whose state cannot be modified after it is created.

**What is Referential transparency?**

The dependency of a foreign key on a primary key. Each foreign key must correspond to a primary key on that table.

**What is a module?**

A piece of functionality encapsulated in a file that is separate from the main application.

**What does the word ‘require’ do?**

Allows us to bring the module into the main application or another module.

**How do we bring another module into the file the we are working in?**

Using require('')

**What do we have to do to make a module available?**

Export it using module.exports = <function name>
