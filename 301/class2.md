Anytime a component is updated or state changes then it is rerendered.

The constructor for a React component is called before it is mounted.

If the component is a subclass you should call super(props), or the props will be undefined.

Render is the only required method in a class component.

The render function should not modify the component state because it would cause a lot of bugs by changing the state every time it rerenders.

The default behavior in react is to rerender after every state change.

If you do decide to use this method, be sure to check the previous props and state with the current props and state.
