### Hooks
React hooks allow to to easily create and manage state in a functional component.

Hooks are JavaScript functions, but they impose additional rules:

- Hooks must be named with a use prefix (i.e. useFishingPole)
- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)


### Built In Hooks"

``useState()``

Returns a stateVariable and setterFunction for you to use to manage state in a functional component

**EX:**

1. clicks is the state variable, which will store the number of clicks

2. setClicks is a function that is called to change the value of clicks How does this work?

3. by convention, we use set + statevariable (camel cased) to name this function

4. ``useState()`` takes a single param, which is the initial value to assign to the state variable

5. You can call your setter function .. i.e. setClicks(7) and the attribute value you call the function with is used as the new value for the state variable.

