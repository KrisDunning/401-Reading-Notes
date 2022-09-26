[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 06 - Authentication

## Discussion Questions

### Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password.
> Hashing a password is like you putting a password in a magic box and a number pops out. The black box is the hashing tool. The website only sees the number. You know your password. If anyone steals data from the website all they get is the number. If anyone else enters their password the box spits out a different number than your number. 

What is Bcrypt?
> A password hashing function.

Why might you use something like Bcrypt?
> It is adaptive (future-proof 'ish) so that it can keep up with improved computing power in the future. It is intentionally "slow" for setting up to counter brute-force attacks.

### Basic Auth

What is Basic Authentication?
> A method for HTTP requests to include username and passwords when making requests.

What properties are necessary in the header of a Basic Auth request?
> Authorization: Basic |credentials| where credentials is the Base64 encoding of ID and password joined by a single colon : .

How are username:password in Basic Auth encoded?
> Base64 encoded.

### OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter.
> The process is submitting username, password and a unique additional item. Sometimes a unique key-phrase or code. When these are supplied to the website they check for mathching information and either grant access or deny access.

How should your error messaging respond (both HTTP and HTML)? Why?
> In a generic manner. Simple HTML response like "Login failed: Invalid User or Password". For HTTP it should only respond with the response number and not provide any content as part of the response.
> The reason why is that malicious attackers can use any additional information to slowly learn details of the technology used and what type of information is correct so as to narrow their window of attack.

## Things I want to know more about

I am inadequately educated on hash tables and salting a hash. I need to brush up on this area.

-----
