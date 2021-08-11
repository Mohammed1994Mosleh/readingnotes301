# class04.

## Controlled Component
1. What is a ‘Controlled Component’?
A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

update the state with their responses as soon as they enter them. because alue attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth

3. How do we target what the user is entering if we have an event handler on an input field?

bu using  textarea tag

## Ternary Operator.

1.Why would we use a ternary operator?
Make Your Code Cleaner with JavaScript Ternary Operator

2. (x===y)? console.log(true):console.log(false)