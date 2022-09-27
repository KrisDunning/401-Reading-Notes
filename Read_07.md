[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 07 - Bearer Authorization

## Discussion Questions

### Intro to JWT

What is a JSON Web Token (JWT)?
>JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

When should we use JSON Web Tokens?
>Authorization: Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token.
> Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties.

Claims are expected in which structural component of a JWT?
> The Payload.

### Are JWTs Secure?

If I get a JWT and I can decode the payload, how can we call that secure?
> Though a JWT can be "signed" if it is not encrypted, anyone can read the contents but cant make any changes if they dont have the private key.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
> A secret.

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
> I put a piece of paper in an envelope and mail it to my friend. Anyone can open the letter and read it, but its written in my hand so any changes will be noticeable as not my handwritin. If I wanted to keep my message secret I would encrypt it and use a secret method known only to me and my friend to conceal the message. Anyone might be able to intercept the letter but wouldn't read the message I sent. Only my friend would get the message because only he and I know that I used invisible ink to conceal the true message in the letter.

### JWTs Explained

Why use JWT?
> Digitally signed. No changes en route. 

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
> Easy to send via URL, POST request and HTTP header. The token itself contains the user info and avoids querying the database more than once.

What are the three components (the structure) of a JWT signature?
> The header, the payload, the signature.

## Things I want to know more about

Just good coding practices for creating, transmitting and storing the JWT's. I have only used them once or twice and I know I did not utilize them to their fullest. I can see how useful it would be to not keep querying the server for user info and I am looking forward to see how to utilize the tokens for both authentication and authorization.

-----
