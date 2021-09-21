# React Lifecycle


1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
    > render

2. What is the very first thing to happen in the lifecycle of React?
    > Mounting ---> constructor

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    > constructor, render, componentDidMount, componentWillMount, React Updates
4. What does componentDidMount do?
    > 

## Notes:
  * The constructor for a React component is called before it is mounted
  * render is the only required method in a class component



## Video

1. What types of things can you pass in the props?
   * display something to the user that has a title or subtitle.
   * arguments
   * for things that you pass through a function
   * what you want to initialize your component to
   * what you want your component to render like

2. What is the big difference between props and state?
    * props you pass into a component. handled outside of a component
    * states are handled inside of a component

3. When do we re-render our application?
    * when you change the state of your application it will rerender that part of your application

4. What are some examples of things that we could store in state?
    * something that might need continueal update bc of user inputs
    * so something inside of a form like a checkbox, select list

    [Back](https://angeladzodzomenyo.github.io/reading-notes/)