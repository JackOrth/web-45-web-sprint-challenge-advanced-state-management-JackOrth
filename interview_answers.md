# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    The main problem that context API helps solve is you no longer have to worry about prop drilling. Context API allows you to store data on a context object, and then pass that data to the components necessary. 

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Store is what is holding all of the data for the application. Actions tell the reducer to manipulate the data in store, and the reducer is what manipulates the data when it receives an action. 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    redux thunk allows us to return a function where work can be done in an asynchronous manner. 

4. What is your favorite state management system you've learned and this sprint? Please explain why!
 Context API... It keeps the code much cleaner!