# Code 301 Reading 4: React and Forms

## [React Docs - Forms](https://reactjs.org/docs/forms.html)

> Form elements in React are different from other DOM elements as they keep an internal state.

___What is a ‘Controlled Component’?___

* In React, a contolled component is one that renders a form and also controls what happens in that form on subsequent user inputs. (https://reactjs.org/docs/forms.html)

___Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.___

* Update state as soon as they submit, it should be contantly storing as they enter so that it can control and update the form as necessary while user interacts.

___How do we target what the user is entering if we have an event handler on an input field?___

have the event handler within input field change the value of the state:

```JavaScript

  handleChange(event) {
    this.setState({value: event.target.value});
  }
// THIS LINE ^^^^ FOR STATE CHANGE
    render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Name:
          <input type="text" value={this.state.value} onChange={this.handleChange} />
        </label>
        <input type="submit" value="Submit" />
      </form>

Code Source: <https://reactjs.org/docs/forms.html>
```

---

## [The Conditional/Ternary Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeffl)

___Why would we use a ternary operator?___

___Rewrite the following statement using a ternary statement:___

```JavaScript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```





---

<===== [BACK!](README.md)
