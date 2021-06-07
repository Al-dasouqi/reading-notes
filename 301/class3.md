# Passing Functions as Props

## Lists and keys 

A "Key" is a special string attribute you need to include when creating lists of elements.

Let's assign a key to our list items inside numbers.

> </li.> );. The best way to pick a key is to use a string that uniquely identifies a list item among its siblings.

If you choose not to assign an explicit key to list items then React will default to using indexes as keys.

If you extract a ListItem component, you should keep the key on the <ListItem /> elements in the array rather than on the <li> element in the ListItem itself.

> // Correct! Key should be specified inside the array.

Keys used within arrays should be unique among their siblings.

## Spread Operator


The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function's arguments.

The spread syntax "Spreads" the array into separate arguments.

One of the best ways to understand the use of spread operator in JavaScript is to look at the the built-in functions Math.min() and Math.max(), which both expect a list of arguments, not an array.

Since the spread operator "Spreads" an array into different arguments, any functions that accepts multiple any number of arguments can benefit from use of the spread operator.

Adding an item to an array in React state is easily accomplished using the spread operator.

"The spread operator can expand another item by split an iterable element like a string or an array into individual elements:" - CodinGame.com.

The spread operator is useful for working with arrays and objects in JavaScript.
