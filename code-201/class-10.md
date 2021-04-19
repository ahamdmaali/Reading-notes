# Error Handling & Debugging
#### When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too. When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it.

## ORDER OF EXECUTION
#### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

## EXECUT.ION CONTEXTS
#### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

### Every statement in a script lives in one of three execution contexts: 
1. GLOBAL CONTEXT : Code that is in the script, but not in a function. There is only one global context in any page. 
2. VAL CONTEXT (NOT SHOWN) : Text is executed like code in an internal function called eva l {) (which is not covered in this book). 
3. GLOBAL SCOPE : If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 

## EXECUTION CONTEXT and HOISTING
#### Each time a script enters a new execution context, there are two phases of activity: 
### PREPARE 
1. The new scope is created 
2. Variables, functions, and arguments are created 
3. The value of the this keyword is determined 
### EXECUTE
1. Now it can assign values to variables 
2. Reference functions and run their code 
3. Execute statements 

## UNDERSTANDING SCOPE 
#### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

## UNDERSTANDING ERRORS
#### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

## ERROR OBJECTS
#### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

## HOW TO DEAL WITH ERRORS 
#### there are two things you can do with the errors:
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

## DEBUGGING WORKFLOW
#### Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues. 

## LOGGING DATA TO THE CONSOLE
#### The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

##### To learn more about Error Handling & Debugging, read duckett JS book, ch10.