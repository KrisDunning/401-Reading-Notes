[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 39 - Redux - Additional Topics

## Discussion Questions

### Redux Toolkit (RTK)

What concerns are addressed by Redux Toolkit?

- 1 "Configuring a Redux store is too complicated"
- 2 "I have to add a lot of packages to get Redux to do anything useful"
- 3 "Redux requires too much boilerplate code"

What does configureStore() do?
> Wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

How would I use createSlice()?
> Accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

### MobX

What is Mobx?
> Simple, scalable and battle-tested state management solution.

How does MobX make it “impossible” to produce an inconsistent state?
> Makes sure that everything that can be derived from the application state, will be derived. Automatically.

How would we build a reactive user interface?
> Setup our application state with our data. We can then setup the derivations, which are directly derived from the app. state. Then we can create some reactions, which are simliar to derivations but they dont produce a value, they perform a task (usually I/O related). Then we have Actions which are the things which alter the state and which MobX uses to ensure all derivatives and reactions are processed automatically.

### Tutorial

What take-away(s) did this tutorial provide?
> The slice seems to be useful due to the fact we can wrap up all our reducers inside and just pass the reducer to the store and it handles all the rest under the hood.

## Reflection

What are your learning goals after reading and reviewing the class README?
> I really need to get my app up and running with the slices/reducers.

## Things I want to know more about

> I am wondering how MobX would work with our current storefront app. I wonder if its worth it to reproduce the same app utilizing MobX instead of Redux to feel out the differences.

-----
