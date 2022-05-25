# Basic JavaScript

## Declare JavaScript Variables

JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.

*var ourName;*

creates a variable called ourName. In JavaScript we end statements with semicolons. Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.

## Understanding Uninitialized Variables

When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a string of undefined.

## Explore Differences Between the var and let Keywords

*let camper = "James";*
*let camper = "David";*

The error can be seen in your browser console.
So unlike var, when you use let, a variable with the same name can only be declared once.

## Understand String Immutability

In JavaScript, String values are immutable, which means that they cannot be altered once created.

## Testing Objects for Properties

Sometimes it is useful to check if the property of a given object exists or not. We can use the *.hasOwnProperty(propname)* method of objects to determine if that object has the given property name. *.hasOwnProperty()* returns true or false if the property is found or not.