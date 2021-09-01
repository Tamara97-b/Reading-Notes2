# Thinking in React


## How would you break a mock into a component heirarchy?
Step 1: Break The UI Into A Component Hierarchy
Step 2: Build A Static Version in React
Step 3: Identify The Minimal (but complete) Representation Of UI State
Step 4: Identify Where Your State Should Live
Step 5: Add Inverse Data Flow
## What is the single responsibility principle and how does it apply to components?
The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

## what does it mean to build a ‘static’ version of your application?
Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.Sep 8, 2014

## Once you have a static application, what do you need to add?
Add Inverse Data Flow
## What are the three questions you can ask to determine if something is state?
can i  be used in Class Components ?
can i updated the value  by event handlers?
should State never be updated explicitly?
## How can you identify where state needs to live?
One of the many great parts of React is how it makes you think about apps as you build them. In this document, we’ll walk you through the thought process of building a searchable product data table using React.