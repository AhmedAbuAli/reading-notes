### This topic is very important becouse it teach you When to use State & Higher-Order Functions
<br>
<hr><hr><hr>
<br>

# Reading

## React Docs - Thinking in React

### What is the single responsibility principle and how does it apply to components?

-  a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

### What does it mean to build a ‘static’ version of your application?

- renders your data model, you’ll want to build components that reuse other components and pass data using props.

### Once you have a static application, what do you need to add? 

-  Add state to components 

### What are the three questions you can ask to determine if something is state?
1) Is the component passed in from a parent using props? 
2) Can you compute it based on any other state or props in your component? 
3) Does it Change Later?

### How can you identify where state needs to live?

1) Identify every component that renders something based on that state.
2) Find a common owner component (a single component above all the components that need the state in the hierarchy).

3) Either the common owner or another component higher up in the hierarchy should own the state.

4) If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

### What is a “higher-order function”?

- Functions that operate on other functions, either by taking them as arguments or by returning them,

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- It is taking a function as an argument and returning a function.

### Explain how either map or reduce operates, with regards to higher-order functions.

- map and reduce operate on arrays.

## Things I want to know more about