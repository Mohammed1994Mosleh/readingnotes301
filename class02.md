# Class02.

## React: Component Lifecycle Events:
* The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.
![lifecycle](https://cdn-media-1.freecodecamp.org/images/1*_drMYY_IEgboMS4RhvC-lQ.png)
lifecycle events:
1. Mounting
2. Updating
3. Unmounting

* note:render() Render is the only required method in a class component. It will examine this.props and this.state when called

- componentDidMount():
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

### lifecycle events:
- constructor()
- static getDerivedStateFromProps()
- render()
- componentDidMount()

- shouldComponentUpdate()
- getSnapshotBeforeUpdate()
- componentDidUpdate()
- componentWillUnmount()
- UNSAFE_componentWillMount()

## Things I want to know more about:
- khnow differnece between state and prop
- UNSAFE Lifecycle Events
- Event in React