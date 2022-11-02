[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 33 - \<Login/> and \<Auth/>

## Discussion Questions

### What is Role Based Access Control (RBAC)?

What is Role Based Access Control (RBAC)?
> Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control.

Share some an example of RBAC including all possible CRUD operations and correlating roles.
> Billing Operations  
> Customer - Role:user, CRUD:Create, Read  
> Customer Service - Role:editor, CRUD: Create, Read, Update  
> Admin - Role: admin , CRUD: Create, Read, Update, Delete

What are the Benefits of RBAC?
> Reduces administration and IT support. Maximizes operational efficiency. Improves complience.

### React-Cookie Library/Component

Compare and Contrast the two Libraries and the following questions. Yes, they are similarly named.

Describe some react-cookie Library features.
> Has a useCookie hook.
> Allows to wrap a componente in a withCookies wrapper to give access to cokkies to another component.
> Server side rendering with cookies

Describe some react-cookies Component features.
> Allows regex search for finding multiple cookies.
> Allows Isomorphic cookies for server side rendering.

Which library would you prefer would you prefer? Why?
> I think the component. It has dot(.) notation for access to methods on cookies.I *think* that would work best for me.

## Reflection

What are your learning goals after reading and reviewing the class README?
> Get Cookites working with Auth of course. But also I need to re-learn local storage to store the user cookie.

## Things I want to know more about

Still need to get used to mantine styles and scss.

-----
