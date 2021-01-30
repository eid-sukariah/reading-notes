# operators & Loops

**Loops** are used in JavaScript to perform repeated tasks based on a condition. 
Conditions typically return `true` or `false` when analysed. 
A loop will continue running until the defined condition returns `false`.

The three most common types of loops are

1. for
2. while
3. do while

![for loop](https://cdn.javascripttutorial.net/wp-content/uploads/2020/01/JavaScript-for-Loop.png)
![while loop](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-while-loop.png)
## Description
* initialization - Run before the first execution on the loop. This expression is commonly used to create counters. Variables created here are scoped to the loop. Once the loop has finished it’s execution they are destroyed.
* condition - Expression that is checked prior to the execution of every iteration. If omitted, this expression evaluates to true. If it evaluates to true, the loop’s statement is executed. If it evaluates to false, the loop stops.
* final-expression - Expression that is run after every iteration. Usually used to increment a counter. But it can be used to decrement a counter too.
* statement - Code to be repeated in the loop

## what loop in 

One of the most common tasks you have to deal with in JSP is outputting a set of data by using the Java for and while loop. By doing so, you create a very unreadability JSP page with opening and closing curly brace. In addition, if something an error occurred, it is difficult to detect the code that causes the problem.

Fortunately, JSTL provides you with two useful actions for looping and iteration: for general data and for a string of tokens.
