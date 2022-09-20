[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 02 - Express, NPM, TDD, CI/CD

## Discussion Questions

### An introduction to NodeJS and Express

1) Explain middleware, answer as though I were a non-technical recruiter.
  > Middleware is code that can be inserted to handle organization and communication between two other pieces of code. Generally addresses a specific need or want that the other two pieces of code do not handle.

2) Express the most popular ___?
  > node web framework

3) Express is “unopinionated.” What does that mean?
  > That express doesn't prefer a specific way to utilize or interact with it from a support point of view. There isn't a "right way" to use it. 

4) What is a module and why is modularity useful to us as developers?
  > Code, a file or library, that can be imported into another piece of code for use. They allow us to re-use code easily simply by choosing which code we want to use and where to use it.

### What is NPM?

1) What version of npm are you running on your machine?
> 8.19.1

2) What command would you type to install a library/package called ‘jshint’ into your node project?
> npm install jshint

### What is TDD?

1) Explain why tests are important. Please explain as though I were your non technical elder.
> Tests are important because they enable us to see if our work is being done properly. Much like a chef taste's a dish as it is being prepared to ensure the quality. Coders test each bit of code to ensure it will work as intended. 

2) What are three expected benefits of testing?
> a) reduction of defect rates  
> b) reduction in efforts in final phases  
> c) reported increase of quality of code

3) Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
> Individual - Not testing often enough. Writing too many tests at once.
> Team - Partial adoption and poor maintenance of test suite.

### CI/CD

1) What are three benefits of Continuous Integration?
> Ensure everyones changes integrate into the main code. Catch bugs in the code. Reduce merge conflict.

2) What is the difference between Continuous Delivery and Continuous Deployment?
> Delivery is the concept that the code that is integrated could be deplyed at any time. Deployment is an extension of delivery and is when you can deploy new features immediately.

3) Explain how GitHub fits into this process assuming the listener comes from a non-technical background
> It's almost like an air traffic controller at the airport. GitHub coordinates all the flights, their information, crew and customers, to handle actions the planes want to do. Take-off,land, etc. GitHub can track everything and If something changes, a delayed flight maybe, can re-route traffic as needed or just advise the aircraft of the impact the changes will make.

## Things I want to know more about

How to write better analogies. It's hard to find a good analogy that is intended for a non-technical audience. Also I should brush up on github actions and what they can be used for in my future work.

-----
