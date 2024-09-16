# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    context API stops the need for props-drilling which can slow the development of the app

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions contain object information that is dispatched to a reducer. 
    Reducer takes state and an action and returns an updated object that contains state. 
    Store will contain the state object that the Reducer creates; it is considered a 'single source of truth' because it is only one storage of global state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Redux-thunk allows the reducer flow to be asynchronous and access the API's from action creators.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    Context API is my favorite so far because it simplifies the props-drilling process