[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 2 - Lifecycle/useEffect Hook

## Discussion Questions

### ffects hook

What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?
> useEffect Hook in function components is as componentDidMount, componentDidUpdate, and componentWillUnmount in class components.

When using the useEffect Hook:

What does useEffect do?
> Allows you to perform side effects in a functional component.

Why is useEffect called inside a component?
> We can accest state or props from inside the scope of the effect.

Explain the importance of properly implementing effects with Cleanup
> They prevent bugs, memory leaks and allow us to include our code all in one place to create easy to read code.

## Reflection

What are your learning goals after reading and reviewing the class README?
> Finding out what other hooks are built into React and what little rules they have as well. I didnt realize that the return function in a useEffect hook was it's cleanup function. Handy.

## Things I want to know more about

More hooks please. Also more about proper functional component data flow and app design. Sometimes I think I know how data should flow and then later realizing my concept wouldn't work out the way I would have liked. Also how to make true API calls from REACT.

-----
