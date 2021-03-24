## Java Notes from 401-Java reading

1. [Arrays, Loops, Imports](#Arrays)
2. [Maps, Primitives, File I/O](#Maps)



#### Arrays Loops Imports

Types of loops are 
- Simple `for` loop
- Enhanced `for-each` loop
- `While` loop
- `Do-While` loop

1. For Loop
    - A for loop is a control structure that allows us to repeat certain operations by incrementing and evaluating a loop counter.

2. While Loop
    - The while loop is Java's most fundamental loop statement. It repeats a statement or a block of statements while its controlling Boolean-expression is true.

3. Do-While Loop   
    - The do-while loop works just like the while loop except for the fact that the first condition evaluation happens after the first iteration of the loop.


#### Maps Primitives File I/O

Java has a two-fold type system consisting of primitives such as int, boolean and reference types such as Integer, Boolean. Every primitive type corresponds to a reference type.

`Integer a = 1;` This works automatically
`int a = new Integer(1)` This needs more info

The decision what object is to be used is based on what application performance we try to achieve, how much available memory we have, the amount of available memory and what default values we should handle.

If we face none of those, we may ignore these considerations though it's worth knowing them.

Reference memory by type...

- boolean – 1 bit
- byte – 8 bits
- short, char – 16 bits
- int, float – 32 bits
- long, double – 64 bits

Arrays make these memory decisions more important as they exponentially increase the amount of memory used based on the value type. 

An Exception is an event that occurs during execution of a program that disrupts the normal flow.

After a method throws an exception, the runtime system attempts to find something to handle it. If no methods on the call stack have a handler for the error, the program will terminate.

For reference the 3 types of Exceptions [Click Here](https://docs.oracle.com/javase/tutorial/essential/exceptions/catchOrDeclare.html)

For reference How to throw an error [Click Here](https://docs.oracle.com/javase/tutorial/essential/exceptions/throwing.html)