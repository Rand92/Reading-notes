## What are component lifecycle events?
React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.
![](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)
### Mounting
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.
### Updating
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
static getDerivedStateFromProps, shouldComponentUpdate, render,
getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate, UNSAFE_componentWillReceiveProps
### Unmounting
The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

shouldComponentUpdate()
The default behavior in react is to rerender after every state change. Setting shouldComponentUpdate() to false allows you to prevent this from happening. This is in order to optimize performance. If you want to use this method, it may be better to use PureComponent instead, which performs a shallow comparison of props and state. If you do decide to use this method, be sure to check the previous props and state with the current props and state. If shouldComponentUpdate() returns false, then UNSAFE_componentWillUpdate(), render(), and componentDidUpdate() will not be invoked.
getSnapshotBeforeUpdate()
This is another rarely used method that allows you to capture a picture of the DOM to check it before actually changing anything on the DOM.
componentDidUpdate()
This method is useful for performing network requests after a change has occurred.
componentDidUpdate(prevProps) {
// Typical usage (don’t forget to compare props):
if (this.props.userID !== prevProps.userID) {
this.fetchData(this.props.userID);
}
}
componentWillUnmount()
This method allows you to clean up the DOM and netwrok requests/ subscriptions.
UNSAFE Lifecycle Events
UNSAFE_componentWillMount()
UNSAFE_componentWillUpdate()
UNSAFE_componentWillReceiveProps()
These events have lead to a lot of bugs and unintended side effects, so in React 17 these will no longer be able to be used without the UNSAFE tag in front of them. Instead of componentWillMount use ComponentDidMount.
Instead of componentWillReceiveProps use static getDerivedStateFromProps.
Instead of componentWillUpdate us getSnapshotBeforeUpdate.

What is a Linked List?
A linked list is a linear data structure where each element is a separate object usually called a node. A node is comprised of the data and a reference to the next node. The last node has a reference to null. The head of the linked list is not a separate node. It is a reference to the first node. If the list is empty then the head is a null reference. This type of linked list is called a singly linked list.