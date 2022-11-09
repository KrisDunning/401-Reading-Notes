[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 38 - Redux - Asynchronous Actions

## Discussion Questions

### async actions

Why use Redux middleware?
> Because we must not introduce side effects inside of our reducers and middleware allows us to use side effects safely.

Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
> Normally when we interact with a site, we use Redux to send a message to update our state store. Middleware allows us to do additional processing steps before we update our state. It modularizes our "business logic" before we update state and then UI.

How are we accommodating async in our Redux app?
> Use Redux's built in middlerware, Redux 'Thunk' Middleware.

### thunk middleware

Why would you need redux-thunk middleware?
> It allows writing functions with logic inside that can interact with a Redux store's dispatch and getState methods.

Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
> function

Describe how any return value from the inner thunk function will be made available.
> It will be available as the return value of the dispatch.

## Reflection

What are your learning goals after reading and reviewing the class README?
> Actually completing the storefront app, utilizing all the tools covered.

## Things I want to know more about

How to better implement the dispatch and update the actual react components.

-----
