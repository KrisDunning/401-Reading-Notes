[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 03 - Express Rest API

## Discussion Questions

### Review: ES6 Classes

1)Classes are a template for creating ____.
> Objects.

2)Can a class declaration be hoisted?
> No they can not.

3)How would you describe a constructor and contextual “this” to a non-technical friend?
> A constructor is like a set of rules for card games like Uno. When you get the game the constructed rules are included in the game. "This" works like a +2 card. It belongs to Uno and only applies to Uno, so no going to vegas and tring to use to bust the dealer.

### Using Express Routing

1)Within Express, what does routing refer to?
> How an applications endpoints respond to client requests.

2)What is the difference between a route path and a route method?
> Route paths define the endpoints at which requests are made. Route methods are derived from HTTP methods. Route methods are what you want to do at the route path. GET, POST etc.

3)When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
> When there is more that one callback function. Make sure to call next in the body of the method.

### Express Routing

1)What is an Express Router?
> A mini express application with only the routing stuff.

2)By what mean do we initialize express.Router() in an express server?
> Declare a variable and assign it the value of express.Router(). Which allows us to utilize multiple express.Router's.

3)What do we use route middleware for?
> To do something before a request is processed. Console logging or data checking, etc.

## Things I want to know more about

How to properly chain together routers, callbacks and path's to mesh cleanly together. I get the feeling we will be learning this very soon. 

-----
