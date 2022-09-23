# Readings: Putting it all together

**React Docs - Thinking in React**

- What is the single responsibility principle and how does it apply to components?

Every class, module, or function in a program should have one responsibility/purpose in a program
- What does it mean to build a ‘static’ version of your application?

Static applications render in the user's browser without the need for server side processing.
- Once you have a static application, what do you need to add?

A minimal UI state.
- What are the three questions you can ask to determine if something is state?

Is it passed in from a parent via props? If so, it probably isn’t state. Does it remain unchanged over time? If so, it probably isn’t state. Can you compute it based on any other state or props in your component? If so, it isn’t state.
- How can you identify where state needs to live?


Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


**Higher-Order Functions**

- What is a “higher-order function”?

Higher Orders Functions are functions that perform operations on other functions.
- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Returning m only if m is greater than n.
- Explain how either map or reduce operates, with regards to higher-order functions.


The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.
## Things I want to know more about.

- React React React
