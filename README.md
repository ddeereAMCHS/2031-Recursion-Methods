# Recursion Methods

## Due: Thur 10/12 at 11:59 PM

- Create a program called `RecursiveMethods.java`
- Create a method that takes an integer n as input and calculates n factorial
  - fact(n) = n * (n-1) * (n-2) * ... * 2 * 1
- Create a method that takes an integer n as input and calculates the n-th number in the Fibonacci sequence
  - fib(n) = fib(n-1) + fib(n-2)
  - You need to figure out what your base case should be
- Create an isOdd method that takes an integer n as input and returns `true` or `false` based on whether n is odd or not
  - You must calculate this recursively, no modulus
- Inside the main method
  - Prompt the user for a number and call the factorial method with that number as a parameter
  - Prompt the user for a number and call the fibonacci method with that number as a parameter
  - Prompt the user for a number and call the isOdd method with that number as a parameter
  - Print the result of the factorial method
  - Print the result fibonacci method
  - Print "even" or "odd" depending on the result of the isOdd method

Example Input:\
4\
4\
4\
Example Output:\
24\
2\
even
