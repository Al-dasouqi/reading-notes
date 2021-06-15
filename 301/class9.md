# Concepts of Functional Programming in Javascript

An impure function would receive radius as the parameter, and then calculate radius * radius * PI:.Why is this an impure function? Simply because it uses a global object that was not passed as a parameter to the function.

Given a parameter A expect the function to return value B.Given a parameter C expect the function to return value D.A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.

The idea of functions as first-class entities is that functions are also treated as values and used as data.

The idea is to treat functions as values and pass functions like data.

These functions have similar logic, but the difference is the operators functions.

If we can treat functions as values and pass these as arguments, we can build a function that receives the operator function and use it inside our function.

The doubleOperator function we implemented above is a higher-order function because it takes an operator function as an argument and uses it.
