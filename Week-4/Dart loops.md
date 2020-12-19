# Dart Programming - Loops

<p>At times, certain instructions require repeated execution. Loops are an ideal way to do the same. A loop represents a set of instructions that must be repeated. In a loop’s context, a repetition is termed as an iteration.</p>

<p>The following figure illustrates the classification of loops</p>

![Classification of loops](https://www.tutorialspoint.com/dart_programming/images/classification_of_loops.jpg)

### Definite Loops

<p>Let’s start the discussion with Definite Loops. A loop whose number of iterations are definite/fixed is termed as a definite loop.</p>

```
for loop
```
<p>The for loop is an implementation of a definite loop. The for loop executes the code block for a specified number of times. It can be used to iterate over a fixed set of values, such as an array</p>

```
for.....in Loop
```
<p>The for...in loop is used to loop through an object's properties.</p>

------

### Indefinite loop

<p>Moving on, let’s now discuss the indefinite loops. An indefinite loop is used when the number of iterations in a loop is indeterminate or unknown. Indefinite loops can be implemented using</p>

```
while Loop
```
<p>The while loop executes the instructions each time the condition specified evaluates to true. In other words, the loop evaluates the condition before the block of code is executed</p>

```
do....while Loop
```
<p>
The do…while loop is similar to the while loop except that the do...while loop doesn’t evaluate the condition for the first time the loop executes.</p>

------

### Loop Control Statements

<p>Let us now move on and discuss the Loop Control Statements of Dart</p>

```
break Statement
```
<p>
The break statement is used to take the control out of a construct. Using break in a loop causes the program to exit the loop. Following is an example of the break statement.</p>

```
continue Statement
```
<p>The continue statement skips the subsequent statements in the current iteration and takes the control back to the beginning of the loop.</p>

### Labels

<p>A label is simply an identifier followed by a colon (:) that is applied to a statement or a block of code. A label can be used with break and continue to control the flow more precisely.

Line breaks are not allowed between the ‘continue’ or ‘break’ statement and its label name. Also, there should not be any other statement in between a label name and an associated loop.</p>


