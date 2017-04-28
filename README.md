# nyt-react-search

##Props



##State



##The Component Lifecycle

###Mounting

####Methods:
-constructor()
-componentDidMount()
-render()
componentDidMount()

Methods componentWillMount() and componentDidMount() run when a component is being created and inserted in to the DOM, componentWillMount() is called before mounting, and componentDidMount() is called after mounting. The render() method will inspect the props and state for the component that is calling the method, and will either return a single react element, null, or false.

###Updating

####Methods:
-componentWillReceiveProps()
-shouldComponentUpdate()
-componentWillUpdate()
-render()
-componentDidUpdate()

render() will not be called if shouldComponentUpdate() returns flase

###Unmounting

####Methods:
-componentWillUnmount()