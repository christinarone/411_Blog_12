# 411_Blog_12
Discuss in words something you learned in class today or this week.
  I learn about how thunks enable us to avoid directly causing side effects in our actions, action creators, or components.
  
What are “actions” in Redux?
  Actions are the only source of information for the stores as per Redux documentation.
  
What is the role of reducers in Redux?
  A reducer is an action and the previous state of the application and returns the new state.

What is the meaning of “single source of truth” in Redux?
  It means that the only way to change your data in UI is to dispatch redux action which will change state within the redux reducer.
  
Explain the working pieces of Redux.
  There is a central store that holds the entire state of the application. Each component can access the stored state without having to send down 
  props from one component to the other. There are three building parts: actions, store, and reducers.
  
Which (if there is) node library method could you use to solve the algorithm problem you solved in class today?
  I have no idea what library method would be the correct one to use.
