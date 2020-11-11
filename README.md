# Lab 23 - Recursive Fib and Fact

In Lab 19 you generated iterative implementations of the Fibonacci sequence and the Factorial calculation.  In this lab you will be creating recursive implementations of both of those algorithms.  Try to implement them yourselves, but if you get stuck there is some help at the bottom of this file.

### Fibonacci Sequence ###

This function will accept one parameter `num` which is the number of Fibonacci numbers to output.  For example, if `num` is 5, then you should print the first 5 numbers in the Fibonacci sequence.

### Factorial ###

This function will accept one parameter `num` which is the number to return the factorial of.  For example, if `num` is 5, then you should return 120.

### Tests ###

There are no tests for this lab, so check your output against the samples below.

### Factorial ###

Sample Input | Expected Output
-------------|----------------
0 | 1
1 | 1
2 | 2
3 | 6
4 | 24
5 | 120
10 | 3628800

### Fibonacci Sequence ###

These are the first 29 numbers in the Fibonacci Sequence.

`0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610, 987, 1597, 2584, 4181, 6765, 10946, 17711, 28657, 46368, 75025, 121393, 196418, 317811`

### Algorithm Help ###

**Fibonacci**

return n if n == 0, n == 1
return fib(n-1) + fib(n-2) otherwise

**Factorial**

return 1 if n == 1
return n * fact(n-1) otherwise