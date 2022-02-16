# Code 301 Reading 2: State and Props

## [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

* Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  
  * render occurs before ‘componentDidMount’

* What is the very first thing to happen in the lifecycle of React?

  * The mounting phase which is the point when a component is inserted into DOM

* Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

  1. constructor

  2. render

  3. React Updates

  4. componentDidMount

  5. componentWillUnmount

* What does componentDidMount do?

  * it is utilized after a component is mounted successfully when we want to load something using network request or initialize the DOM.

  ---

## [React Bootstrap](https://react-bootstrap.github.io/)

* Replacement for Bootstrap JavaScript

* "The React component model gives us far more control over form and function of individual components" - https://react-bootstrap.github.io/

---

## [Netlify](https://www.netlify.com/)

* This is the way we shall deploy our current apps

* Create web frontends and backend apis using Netlify

* Contains many built-in apps for dynamic functionality.

---

## [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

* Data management and proper re-rendering when something changes are two of the best assets of React.

* What types of things can you pass in the props?

  * when we're handling info outside component.

  * things you want to initialize component to or what you want component to render like

    * Ex: initial count on counter component pass initial count as zero in props

  * When displaying something to user with title and subtitle

    * re renders if props change

  * Used when you want to display info in component without hard-coding it  

* What is the big difference between props and state?

  * State is handled ___inside___ component

  * Props are passed into component from ___outside___

    * Props are changed outside of app

* When do we re-render our application?

  * anytime we change the state inside application

* What are some examples of things that we could store in state?

  * when we need to re-render and update application based on something the user does

  * inside a form input element, use state to store what we're updating value to

  * If we're handling within component and inside only, then use state

---

## Things I want to know more about

1. Practice using props and states in react to become more familiar.

---

### Sources Used

* <https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093>

* <https://react-bootstrap.github.io/>

* <https://www.netlify.com/>

<===== [BACK!](README.md)
