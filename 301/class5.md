# Thinking in react

If you're familiar with the concept of state, don't use state at all to build this static version.

Can you compute it based on any other state or props in your component? If so, it isn't state.

If you can't find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

ProductTable needs to filter the product list based on state and SearchBar needs to display the search text and checked state.

State = to FilterableProductTable's constructor to reflect the initial state of your application.

Now it's time to support data flowing the other way: the form components deep in the hierarchy need to update the state in FilterableProductTable.

Since components should only update their own state, FilterableProductTable will pass callbacks to SearchBar that will fire whenever the state should be updated.
