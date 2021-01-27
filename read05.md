# Comparison and logical operators

## Comparison operators:

+ Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
+ Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
+ Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
+ Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
+ Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
+ Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

![image comparison ops](https://cdn.javascripttutorial.net/wp-content/uploads/2016/11/JavaScript-Comparison-Operators.png)

## Logical Operators
+ && (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
+ || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be false.
+ var is True = ('yellow' === 'green') && (4 >= 4);
+ In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
+ The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
+ The second expression is true, because the number 4 is greater than or equal to 4.
+ The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is false and evaluates too false.

![image logical ops](https://cdn.educba.com/academy/wp-content/uploads/2020/01/Logical-Operators-in-JavaScript.jpg)

# LOOPS 

*The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.*

There are four types of loops in JavaScript.

1. for loop: iterates the elements for the fixed number of times. It should be used if number of iterations is known.


![image for](https://cdn.programiz.com/sites/tutorial2program/files/javascript-for-loop.png)


2. while loop: iterates the elements for the infinite number of times. It should be used if number of iterations is not known.

![image while](https://cdn.programiz.com/sites/tutorial2program/files/javascript-while-loop.png)


3. do-while loop: iterates the elements for the infinite number of times like while loop. But code is executed at least once whether condition is true or false.

![image do-while](https://cdn.programiz.com/sites/tutorial2program/files/javascript-do-while-loop.png)

4. for-in loop: iterate the properties of an object. 
