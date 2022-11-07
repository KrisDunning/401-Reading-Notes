[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 36 - Application State with Redux

## Discussion Questions

### Dan Abramov Redux Tutorials

What is the first principle of Redux?
> Keeping track of all state in a single object location, the state object tree.

what is a store and what do we use our reducers for within that store?
> The location where we store our single source of truth, the state object tree.

Name three Redux store methods given to us by createStore and describe their use.
> getState() - retrieves the state object tree from store.
> dispatch() - dispatches a store action to change state of the application.
> subscribe() - allows you to register a callback to do something when a action is dispatched. Updates UI.

Explain to a non-technical recruiter what combineReducers() does and why it is useful.
> It bundles together multiple reactions to an update in the state object. Like when it's lunch time and your state enters "hungry". Your state updates and your actions now dispatch the "get food", "get water", "wash hands" actions and update the state that these actions were performed.

## Reflection

Looking ahead at this module’s course schedule, What do you look forward to learning?
> Honestly the personal presentation. I am thinking about how much/how little I know about my cohort peers and am wondering if I go to talk to a recruiter and the job is not a good fit for me, would I be able to reccommend a peer that might be a good fit?

What are your learning goals after reading and reviewing the class README?
> Redux is a crucial part of a React portfolio project. I will definately need to have a decent general understanding of how to use it and demonstrate in a portfolio project.

## Things I want to know more about

What portfolio project would be a good fit for a React/Redux excample? Can I help some friends who need a webpage to display their small business?

-----
