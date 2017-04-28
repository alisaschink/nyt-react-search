# nyt-react-search

## Props



## State



## The Component Lifecycle

### Mounting

#### Methods:
- constructor()
- componentDidMount()
- render()
- componentDidMount()

Methods componentWillMount() and componentDidMount() run when a component is being created and inserted in to the DOM, componentWillMount() is called before mounting, and componentDidMount() is called after mounting. The render() method will inspect the props and state for the component that is calling the method, and will either return a single react element, null, or false.

### Updating

#### Methods:
- componentWillReceiveProps()
- shouldComponentUpdate()
- componentWillUpdate()
- render()
- componentDidUpdate()

The method componentWillReceiveProps() is called when a component is about to receieve new props. shouldComponentUpdate() is called when a component is receiving new props or state and needs to be rerendered. componentWillUpdate() is called right before a component is re-rendered after an update to props or state. Currently, render() and componentWillUpdate() will not be called if shouldComponentUpdate() returns flase. componentDidUpdate is called right after updating occurs.

### Unmounting

#### Methods:
- componentWillUnmount()