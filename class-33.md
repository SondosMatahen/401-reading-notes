# Class 33 - Reading

## Context
- Context provides a means of passing state down the component tree through a Provider/Consumer relationship.

- At as high a level as makes sense, a “provider” can make it’s state available, along with means of altering it (methods).

- In a functional component, you can use the useContext() hook to tap right in.

- Returns and provides access to whatever your context provider exports

- In this example, our context provider gives us a title property and a changeTitleTo() method that we can call. This is much easier than referencing the context variable inline as you normally would.

- Note – the context API is still critically important even with this hook available. Not every React shop is using hooks, so know both ways.

