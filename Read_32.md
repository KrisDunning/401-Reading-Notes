[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 32 - Context API - Behaviors

## Discussion Questions

### Hooks and Context example

With regard to the React Context API, what does a “provider” do?
> The provider is the centralized component responsible for rendering its state. It also exposes a way to allow global state management.

With regard to the React Context API, how would we implement a “consumer” role?
> We would use the useContext() hook. It takes the context provider as an argument and we can now access the provider.

Specifically with Context, how are we “wrapping” components to achieve our goals?
> We can wrap different functions at different levels to allow access and passing of state between the context consumer and the context provider.

### Awesome React Context links

Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
Takeaway 1:
> Context providers can only be passed "one" child element. So you have to make sure whatever is passed is wrapped in a single element (i.e. div)

Takeaway 2:
> The Wes Bos video was a good walkthrough that helped me understand a little more. Also I listen to his podcast so BONUS!

## Reflection

What are your learning goals after reading and reviewing the class README?
> Goal remains to not just do the assignments but to grok the material. It's a lot of info to take in and I am just hoping that I can retain it all. 

## Things I want to know more about

Efficient usage of context. I feel like contexts should definitely be broken apart into their own file/folders and integrated with consuming. But also how does the useEffect tie in at the child component level if it interacts with the context component.

-----
