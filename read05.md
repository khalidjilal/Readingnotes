# read05 
# Expressions and operators
## This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.

## A complete and detailed list of operators and expressions is also available in the reference.
# Operators
## JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.
## JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:
## Assignment operators
## An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

## There are also compound assignment operators that are shorthand for the operations listed in the following table
# ![](https://image1.slideserve.com/1720651/operators-and-expressions-l.jpg)
# Loops and iteration
# ![](https://149351115.v2.pressablecdn.com/wp-content/uploads/2020/09/The-Loop-series.png)
## Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

## You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:
## There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

## The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.
## for statement
## A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

## When a for loop executes, the following occurs:

## The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
## The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
## The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
## If present, the update expression incrementExpression is executed.
## Control returns to Step 2.