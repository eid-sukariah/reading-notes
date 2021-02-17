# Error Handling & Debugging
- ORDER OF EXECUTION
- EXECUTION CONTEXTS
### the stack
Stacks are data structures that follow the Last-In-First-Out (LIFO) principle, meaning the last item inserted into a stack is the first one to be deleted.
In other words, a stack is a list of elements that are accessible only from one end of the list, which is called the Top of Stack (ToS).

Each time a script enters a new execution context, there are two phases
of activity: 
1. prepare
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined
2. execute
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements
**scope**In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

**errors** If a JavaScript statement generates an error, then it throws an *exception*. At that point, the interpreter stops and looks for exception-handl ing code.

ERROR OBJECTS 
When an Er ror object is created, it will contain the following *properties*:

There are *seven* types of built-in error objects in JavaScript. You'll see them on the next two pages: 

Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY

##  Debugging is about deduction: 
eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues. 
The **console** will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter. 

- You can also just type code into the console and it will show you a result

