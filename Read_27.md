[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 27 - useState Hook

## Discussion Questions

### Introducing Hooks

What was the motivation for introducing Hooks?
> React doesn't have a way to attach reusable behavior to a component. Therefore making it hard to reuse stateful logic between components.

What changes are important regarding implementing Hooks versus Component Classes?
> Class components can encourage unintentional patterns. Classes present issues for today’s tools, classes don’t minify very well, and they make hot reloading flaky and unreliable.

Hooks allow you to reuse stateful logic without changing ______.
> component heirarchy

### hooks api

Name two rules imposed by React Hook usage.
>Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
>Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.

How would you identify a custom Hook and why might you create one?
> If it uses the useSomething naming convention. It allows you to reuse stateful logic between components without adding more components to your tree.

### the state hook

What is a Hook?
> Javascript functions with a few rules imposed on them.

When would I use the useState Hook?
> When I want to manage state in a functional component.

If you were to add React state to a function component by declaring a state variable:

What does calling useState do?
> Allows us to add state management to a functional component.

What do we pass to useState as an argument?
> An initial value to set the state value to.

What does useState return?
>R eturns a stateVariable and setterFunction for you to use to manage state in a functional component

## Reflection

What are your learning goals after reading and reviewing the class README?
> create a fully "functional componenet" React app utilizing custom hooks.

## Things I want to know more about

How to use custom hooks to make an app more effecient and appealing to use. Also how to use SCSS better. Not confident in my CSS/SCSS skills. Rusty since it's been a while since 301.

-----
