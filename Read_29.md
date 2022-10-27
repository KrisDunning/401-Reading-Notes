[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 29 - Advanced State with Reducers

## Discussion Questions

### useReducer hook

Name an alternative to the useState Hook.
> The useReducer hook.

Why might the useReducer Hook be preferable to the useState Hook?
> When you have complex state logic or next state depends on previous state, useReducer improves the ability to handle this and optimize performance.

What are two ways to set the initial state?
> Pass it in as 2nd argument
> Lazy initialization by passing in an init function as 3rd argument

### Ultimate Guide to useReducer

In terms of state, what does useReducer expect to receive as a parameter?
> 1st is a reducer function and 2nd is the initial state

What does useReducer return?
> An array containing current state value and a dispatch action.

Explain dispatch to a non-technical recruiter.
> It's an action to take to update our state or our current data. If I say I have 5 apples and I take a dispatch action, now I have 10 apples. The dispatch action is what we did the change the 5 apples to 10. In this instance the dispatch was take current state and multiply by 2.

## Reflection

What are your learning goals after reading and reviewing the class README?

> Just to get a working version of useReducer and its dispatch. Maybe check out a few REDUX articles/videos to get more general familiarity with an industry tool.

## Things I want to know more about

REDUX and useLayoutEffect. Seems like both are standard for the industry. 

-----
