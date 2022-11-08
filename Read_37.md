[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 37 - Redux - Combined Reducers

## Discussion Questions

### Multiple Reducers Example

Why create multiple reducers?
> For organizing our code into smaller single responsibility purposes. Instead of creating a monolith reducer.

How would you combine multiple reducers?
> use the combineReducers function from Redux. The have a reducer selector reducer. Pass in the name and payload you want to pass to a specific reducer then the reducer selector finds the child reducer and passes the info to who needs it.

How will you manage state as an immutable object? why?
> We must make a new state object. Either assign state to a new variable or use the spread operatoer (...state)

### Redux Docs: Using Combined Reducers

combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
> Redux Reducers

Explain how combineReducers assembles the new state tree.
> Calls all "slice" reducers and gives them the chance to respond and update its "slice" of state.

How would you define initial state in an app using combineReducers?
> Have the root reducer return the initial state value when the state argument is undefined.

### Redux Docs: Combined Reducer Syntax

Why will you want to split your reducing functions as your app becomes more complex?
> Allows you to comine the functions as children under a root reducer to gather results into a single state object.

The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
> Combine Reducers

What is a popular convention when naming reducers?
> Name them after the state slices that they manage.

## Reflection

What are your learning goals after reading and reviewing the class README?
> Actually getting all these pieces to work together to make a funtional storefront

## Things I want to know more about

Could React/Redux be used to make a mini version of a content management system/admin control panel.

-----
