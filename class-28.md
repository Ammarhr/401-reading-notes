## Forms and Inputs

### FORMS:
- An input form element whose value is controlled by React in this way is called a controlled component.
- HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.
- This form has the default HTML form behavior of browsing to a new page when the user submits the form.

### PROP:
- Components accept arbitrary inputs called props.

- In JSX, props are passed into a component with a syntax that looks like HTML attributes.

- Props is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on props. After props is passed into the constructors super function, they are available on the context by using this.props.

### One Way Data flowLinks:
- State can only be passed from parent component to a child component through the use of props. This enforces the idea of one way data flow.
- One way data flow is a way of describing that state can only be passed down the component tree (not up).
-If a child wants to pass some data to a parent, the parent can pass a function to the child through props and the child may invoke that function and pass it data for the parent to manage.
