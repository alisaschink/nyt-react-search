# nyt-react-search

## Props

In React, Props are arbitrary inputs attached to each component. They are considered to be a way to pass data from parent component to child component. Components shouldn't ever modify its own props

## State

State is a representation of a component's data at a given point in time. Anytime data for a component is being updated, this.setState() will need to be called to update the state for that component. 

## The Component Lifecycle

### Mounting

#### Methods:
- constructor()
- componentDidMount()
- render()
- componentDidMount()

#### Description:
Methods componentWillMount() and componentDidMount() run when a component is being created and inserted in to the DOM, componentWillMount() is called before mounting, and componentDidMount() is called after mounting. The render() method will inspect the props and state for the component that is calling the method, and will either return a single react element, null, or false.

### Updating

#### Methods:
- componentWillReceiveProps()
- shouldComponentUpdate()
- componentWillUpdate()
- render()
- componentDidUpdate()

#### Description:
The method componentWillReceiveProps() is called when a component is about to receieve new props. shouldComponentUpdate() is called when a component is receiving new props or state and needs to be rerendered. componentWillUpdate() is called right before a component is re-rendered after an update to props or state. Currently, render() and componentWillUpdate() will not be called if shouldComponentUpdate() returns flase. componentDidUpdate is called right after updating occurs.

### Unmounting

#### Methods:
- componentWillUnmount()

#### Description:
The method componentWillUnmount() is called immediately before a component is going to be unmounted and destroyed. 