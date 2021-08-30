# react lifecycle
## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
When a component is mounted it is being inserted into the DOM. This is when a constructor is called. componentWillMount is pretty much synonymous with a constructor and is invoked around the same time. componentDidMount will only be called once after the first render. 
## What is the very first thing to happen in the lifecycle of React?
The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
## What does componentDidMount do?
onstructor
getDerivedStateFromProps
render
componentDidMount
componentWillUnmount
 ## What types of things can you pass in the props?
 any data type,
## What is the big difference between props and state?
state is internal and controlled by the component itself
props are external and controlled by whatever renders the component
## When do we re-render our application?
whenever there is a change in their state or props
## What are some examples of things that we could store in state?
 if we have form and will be updated by users

 ## Things I want to know more about
 more about state