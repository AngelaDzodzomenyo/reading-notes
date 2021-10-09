# Readings: Putting it all together

## Reading - React Docs - Thinking in React
-----------

1. What is the single responsibility principle and how does it apply to components?

> A component should ideally only do one thing. Separate your UI into components, where each component matches one piece of your data model. 

2. What does it mean to build a ‘static’ version of your application?

> It will render you a data model.

3. Once you have a static application, what do you need to add?

> You'll want it to be interactive, you want to be abke to trigger changes. So you'll want to add state.

4. What are the three questions you can ask to determine if something is state?

> Is it passed in from a parent via props? If so, it probably isn’t state.

> Does it remain unchanged over time? If so, it probably isn’t state.

> Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live? [Step 4: Identify Where Your State Should Live](https://reactjs.org/docs/thinking-in-react.html)

> Identify every component that renders something based on that state.

> Find a common owner component (a single component above all the components that need the state in the hierarchy).

> Either the common owner or another component higher up in the hierarchy should own the state.

>If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions
-------------------------

1. What is a “higher-order function”?

> Functions that operate on other function, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

> Its a function that creates a new function. Basically youre comparing two numbers that returns true/false if the argument is greater than 10, in this case the argument is 11. 

3. Explain how either map or reduce operates, with regards to higher-order functions.

> Reduce builds a value by reapeatedly taking a single element from the array and combining it with the current value. 