# error handling & debugging
JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

## execution context:
Every statement in a script lives in one of three execution contexts:
1. global context:
Code that is in the script, but not in a function. There is only one global context in any page.
2. eval context: 
Text is executed like code in an internal function called eva l {) (which is not covered in this book).
3. global scope:
If a variable is declared outside a function, it can be used anywhere because it has global scope If you do not use the var keyword when creating a variable, it is placed in global scope.

![img](https://miro.medium.com/max/700/1*nkt22Vtg22VZRPw1Rl_31Q.png)

## Each time a script enters a new execution context, there are two phases of activity:
1. prepare 
2. excute

## understanding scope:
In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

## UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code

## HOW TO DEAL WITH ERRORS
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY







