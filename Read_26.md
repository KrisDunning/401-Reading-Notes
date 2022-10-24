[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 26 - Component Based UI

## Discussion Questions

### react hello world

What are the building blocks of a React app?
> Elements and Components

What is the difference between an element and a React component?
> An element describes what we want on the screen and a component is a collection of these elements.

What are some advantages of React’s component based architecture?
> It describes what the DOM should be at any given moment. So we can adjust how we want it to look at point A and point B and let React handle the work. It also makes elements and components like puzzle pieces that can be changed/added/removed as we see fit.

### introducing JSX

What is JSX and why do we use it?
> A syntax extension of JavaScript. JSX produces the react "elements" we will render in the DOM.

Describe the process of embedding JavaScript expressions in JSX.
> We utilize curly braces ({ }) to embed JS expressions in JSX.

Is it safe to embed user input in JSX? Explain.
> Yes. By default React converts everything to a string before being rendered.

### rendering elements

Explain what a React Component is to a non-technical friend.
> A collection of things that you might see on a website. Like a comment, with an avatar picture. 

Describe mutability and React Components, specifically, how is the UI updated?
> React elements are immutable, they dont change. Instead we create and replace it by passing it to root.render().

If changes are made to the UI, what does React update?
> Only the elements that change.

## Things I want to know more about

How will we utilize functional components. We used class components before and I had a bit of trouble with state maintenance. I hope using functional components will help with my comprehension of React and use it to it's fullest possibilities.

-----
