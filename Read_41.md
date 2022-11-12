[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 41- React Native

## Discussion Questions

### getting started with react native

Name three Core Components of React Native and describe what they do.
> View - A container that supports layout with flexbox, style, some touch handling, and accessibility controls.
> Text - Displays, styles, and nests strings of text and even handles touch events.
> Imge - Displays different types of images.

What problem does React Native solve (why call it native)?
> Allows you to use JavaScript to write React Components that will be converted to Android or IOS views. So that your app looks and feels like it was written in the native language for those operating systems.

What are the building blocks of a React Native app? How does that compare to a React app?
> You can basically use any React feature like hooks, state, props etc. The React Native components are text,view,text input, scroll view, stylesheets, buttons, switch(renders visual boolean not a switch case statement) and list views. These are just components that React Native can use between Android and IOS OS's. So they compare almost 1 to 1 to React components with some minor differences as noted in the React Native Component API page. 

### expo

What solution does expo provide?
> It is a npm pachage that provides features to support React Native Apps. Examples are First Class Typescript support, install natively compatible libraries from the command line, Develop Apps without XCode(IOS) or Android Studio.

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
> managed workflow

What is the difference between React Native and Expo?
> Expo provides a suite of features that make it easier to develop, and scale complex React Native applications. It is an addition to React Native that adds features such as First Class Typescript support, install natively compatible libraries from the command line, Develop Apps without XCode(IOS) or Android Studio.

### expo snack

Checkout this tool. What does snack allow you to do?
> It's an open-source platform for running React Native apps in the browser. You can write React Native code and run it directly in Expo Go or even in the browser. When you want to share the code, save it and share the URL, or embed it on your website, like in the React Native and React Navigation documentation sites.

### ejecting

What does “eject” mean within the context of Expo?
> Expo allows you to eject your pure-JS project from the Expo iOS/Android clients, providing you with native projects that can be opened and built with Xcode and Android Studio.

When should you not eject?
> If you want to distribute your app on the platforms app stores. Don't eject. Expo will build binaries for you.
> If you are uncomfortrable working with native code. Ejected Apps require use of XCode or Android Studio.
> If you require Expo's push notifications. After ejecting Expo will no longer manage your push credentials.

Why might you choose to eject?
> Your Expo project needs a native module that Expo doesn't currently support.

## Reflection

Looking ahead at this module’s course schedule, What do you look forward to learning?
> I see rotating a matrix on our code challenge list. That, I have heard, is a not uncommon question for technical/whiteboard interiews. That looks fun.

What are your learning goals after reading and reviewing the class README?
> I want to drop one of my labs into Expo and generate a link to use on my phone. That sounds cool.

## Things I want to know more about

> There are a few alternatives to the 'program in one editor, use on any platform' solution. How does Expo rank among those alternatives?

-----
