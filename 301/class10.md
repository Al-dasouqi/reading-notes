# In memory storage

## Understanding the JavaScript Call Stack

### What It Is And Why It's Necessary
An understanding of the call stack will give clarity to how "Function hierarchy and execution order" works in the JavaScript engine.

The call stack is primarily used for function invocation.

The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.

At the most basic level, a call stack is a data structure that uses the Last In, First Out principle to temporarily store and manage function invocation.

A stack is printed showing how the functions are stack on top each other.

Manage function invocation: The call stack maintains a record of the position of each stack frame.

The browser has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

JSON.parse( ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1.This can be solved by just fixing the syntax, in this case the object should be a JSON.JSON.parse(' ')Some syntax errors like sending a trailing comma when calling a function are handled without error by most recent browsers, but older ones you have to be careful.

The red part of our first example represents the call stack, which is the path that your program has taken to reach the point were you set a breaking point or were you have an error.

Testing is automatically called since it's an IIFE;.obj variable is declared with the function add is called which makes an error being thrown;.

About the light blue part of our earliest example of an error message, that shows up like that when we do not handle errors properly, meaning that anything after that error will not be executed.

An alternative it's to encapsulate our problematic function code with a trycatch which would make an error be thrown but this time, not "Uncaught" so we can send it to a error logging to be checked later and send a fallback to the function so that our code continues without problems.

Error you could have some kind of logging system as pointed before so you can check your client errors and fix them without waiting for a report.

Being able to read error messages and practising debugging is one of your biggest weapons has a developer, do it frequently and with enough time you will notice a great decrease in the time you spend on each error that you find along the way.