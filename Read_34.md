[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 34 - API Integration

## Discussion Questions

### Review API Server Build

Explain the different between a query string parameter and a path parameter.
> The path parameter is a parameter proceeded by a slash. A query string parameter is proceeded by a question mark. 

What would our API URL with a path id parameter be given the following information:  

1.Domain: `http://our-site.com`  // `http://our-site.com`

2.v3  // `http://our-site.com/v3`

3.model name: stuff  // `http://our-site.com/v3/stuff`

4.id: things  // `http://our-site.com/v3/stuff/things`

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
> We can send and receive information from a storage location. We can use Keywords like 'GET', 'POST', 'DELETE' etc. to do that. As long as we follow the recipe needed by the storage location to interpret our request then we are good to go.

### Review Auth Server Build

Describe how you would use middleware to implement basic and bearer auth.
> We take all requests and send them to the middleware. This will determine if the user making the request if who they say they are and also that they have the confirmation to do what they are asking to do.

Describe the handshake necessary to implement OAuth.
> We send a request to a 3rd party authorization server and it verifies that we are who we say we are (using google login for example) and then it will send a token back that is "proof" that the person is verified.

Describe how Role Based Access Control works to a non-technical friend.
> Certain people or roles can only do limited things. So for example in a game, Holy Magic can only be used by a person with the role of "cleric". Bows only for "archer" roles etc. 

## Reflection

What are your learning goals after reading and reviewing the class README?

Remembering how to actually code in basic auth, bearer auth and Oauth.

## Things I want to know more about

Different ways to utilize HTTP calls. Axios, built-in HTTPS, webserver libraries.IDK things like that.

-----
