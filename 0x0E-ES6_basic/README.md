0x0E. ES6 Basics
Description
What you should learn from this project:

All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
Allowed editors: vi, vim, emacs, Visual Studio Code
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the js extension
Your code will be tested using the Jest Testing Framework
Your code will be analyzed using the linter ESLint along with specific rules that we’ll provide
All of your functions must be exported
0. Const or let?
Modify
1. Block Scope
Given what you’ve read about var and hoisting, modify the variables inside the function taskBlock so that the variables aren’t overwritten inside the conditional block.
2. Arrow functions
Rewrite the following standard function to use ES6’s arrow syntax of the function add (it will be an anonymous function after)
3. Parameter defaults
Condense the internals of the following function to 1 line - without changing the name of each function/variable.
4. Rest parameter syntax for functions
Modify the following function to return the number of arguments passed to it using the rest parameter syntax
[5. The wonders of spread syntax](./ 5-spread-operator.js)
Using spread syntax, concatenate 2 arrays and each character of a string by modifying the function below. Your function body should be one line long.
6. Take advantage of template literals
Rewrite the return statement to use a template literal so you can the substitute the variables you’ve defined.
7. Object property value shorthand syntax
Notice how the keys and the variable names are the same?
8. No need to create empty objects before adding in properties
Rewrite the getBudgetForCurrentYear function to use ES6 computed property names on the budget object
9. ES6 method properties
Rewrite getFullBudgetObject to use ES6 method properties in the fullBudget object
10. For...of Loops
Rewrite the function appendToEachArrayValue to use ES6’s for...of operator. And don’t forget that var is not ES6-friendly.
11. Iterator
Write a function named createEmployeesObject that will receive two arguments:
12. Let's create a report object
Write a function named createReportObject whose parameter, employeesList, is the return value of the previous function createEmployeesObject.
13. Iterating through report objects
Write a function named createIteratorObject, that will take into argument a report Object created with the previous function createReportObject.
14. Iterate through object
Finally, write a function named iterateThroughObject. The function’s parameter reportWithIterator is the return value from createIteratorObject.
