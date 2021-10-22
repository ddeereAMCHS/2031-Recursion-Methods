# Recursion

- Create a program called `RecursiveMethods.java`
- Create a method that takes an integer n as input and calculates n factorial
  - fact(n) = n * (n-1) * (n-2) * ... * 2 * 1
- Create a method that takes an integer n as input and calculates the n-th number in the Fibonacci sequence
  - fib(n) = fib(n-1) + fib(n-2)
  - You need to figure out what your base case should be
- Create two methods that takes an integer n as input and returns `true` or `false` based on whether n is even or odd (calculate this recursively, no modulus)
  - One method should be called isEven and the other should be called isOdd
- Inside the main method
  - Prompt the user for a number and call the factorial method with that number as a parameter
  - Prompt the user for a number and call the fibonacci method with that number as a parameter
  - Prompt the user for a number and call the isOdd method with that number as a parameter
  - Print the result of the factorial method
  - Print the result fibonacci method
  - Print "even" or "odd" depending on the result of the isOdd method

Example Input:<br/>
4<br/>
4<br/>
4<br/>
Example Output:<br/>
24<br/>
3<br/>
even
