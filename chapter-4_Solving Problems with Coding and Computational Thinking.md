# Chapter 4: Solving Problems with Coding and Computational Thinking

## 4.1: Defining a Problem

In this chapter, we will use the concept of the **Fibonacci sequence** as an example problem that we can solve with coding and computational thinking. The Fibonacci sequence is a sequence of numbers that is defined by the following rules:

- The first two numbers in the sequence are 0 and 1.
- Each subsequent number in the sequence is the sum of the previous two numbers.

For example, the first few numbers in the Fibonacci sequence are 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, and so on.

The Fibonacci sequence has many interesting properties and applications in mathematics and computer science, and it provides a good example of how to use coding and computational thinking to solve problems. In this chapter, we will explore different ways of defining and solving the Fibonacci sequence problem using different techniques and approaches.

Overall, the goal of this chapter is to show how coding and computational thinking can be used to define and solve problems, and how different techniques and approaches can be used to find solutions to problems. By working through this chapter, you will learn how to define a problem, how to break a problem down into smaller pieces, and how to use different strategies and algorithms to solve the problem.

## 4.2: Identifying the Inputs and Outputs

The first step in solving a problem with coding and computational thinking is to identify the **inputs** and **outputs** of the problem. The inputs are the values or data that are given to the problem, and the outputs are the values or results that are produced by the problem.

For the Fibonacci sequence problem, the inputs are the two starting numbers in the sequence, which are 0 and 1. The outputs are the subsequent numbers in the sequence, which are calculated by summing the previous two numbers.

To solve the Fibonacci sequence problem, we need to define a function or procedure that takes the two starting numbers as inputs, and that produces the subsequent numbers in the sequence as outputs. For example, the following code defines a function called `fibonacci` that takes two `int` parameters called `a` and `b`, and that returns the next number in the sequence as an `int`:

```javascript
func fibonacci(a: int, b: int) -> int {
    // Calculate the next number in the sequence as the sum of the previous two numbers
    var c = a + b

    // Return the next number in the sequence
    return c
}
```


This function defines a simple algorithm for calculating the next number in the Fibonacci sequence, and it uses the inputs `a` and `b` to produce the output `c`. By calling this function multiple times and passing the previous two numbers as arguments, we can generate the entire Fibonacci sequence.

Overall, the first step in solving the Fibonacci sequence problem is to identify the inputs and outputs of the problem, and to define a function or procedure that can be used to generate the outputs from the inputs. By doing this, we have defined a clear and precise problem statement, and we have a concrete plan for solving the problem.


## 4.3: Developing an Algorithm

The next step in solving the Fibonacci sequence problem is to develop an **algorithm** that can be used to generate the sequence of numbers. An algorithm is a sequence of steps or instructions that defines a procedure or method for solving a problem. In the case of the Fibonacci sequence problem, the algorithm defines the steps for calculating the next number in the sequence from the previous two numbers.

There are many different algorithms that can be used to solve the Fibonacci sequence problem, and some of these algorithms are more efficient or more complex than others. In this section, we will explore a few different algorithms for generating the Fibonacci sequence, and we will compare and contrast these algorithms in terms of their performance and complexity.

The first algorithm we will consider is a simple and straightforward approach that uses a `for` loop to iterate over the sequence of numbers. This algorithm defines a `for` loop that starts with the two starting numbers, and that uses the `fibonacci` function defined in the previous section to calculate the next number in the sequence. The algorithm also uses a `print` statement to print each number in the sequence to the console:

```javascript
// Define the starting numbers in the sequence
var a = 0
var b = 1

// Define the number of iterations in the sequence
var n = 10

// Use a for loop to iterate over the sequence
for (var i = 0; i < n; i++) {
    // Call the fibonacci function to calculate the next number in the sequence
    var c = fibonacci(a, b)

    // Print the next number in the sequence
    print(c)

    // Update the starting numbers in the sequence
    a = b
    b = c
}
```

This algorithm is simple and easy to understand, and it uses the `fibonacci` function to calculate the next number in the sequence. However, this algorithm is not very efficient, because it uses a `for` loop to iterate over the sequence of numbers, which can be slow and wasteful.

A more efficient algorithm for generating the Fibonacci sequence is to use a `while` loop instead of a `for` loop. This algorithm defines a `while` loop that starts with the two starting numbers, and that uses the `fibonacci` function to calculate the next number in the sequence. The algorithm also uses a `print` statement to print each number in the sequence to the console:

```javascript
// Define the starting numbers in the sequence
var a = 0
var b = 1

// Define the number of iterations in the sequence
var n = 10

// Use a while loop to iterate over the sequence
var i = 0

while (i < n) {
    // Call the fibonacci function to calculate the next number in the sequence
    var c = fibonacci(a, b)

    // Print the next number in the sequence
    print(c)

    // Update the starting numbers in the sequence
    a = b
    b = c

    // Increment the loop counter
    i++
}
```


This algorithm is more efficient than the previous algorithm, because it uses a `while` loop instead of a `for` loop. This allows the algorithm to be more flexible and efficient.

## 4.4: Implementing the Algorithm in a Programming Language

Once you have developed an algorithm for solving the Fibonacci sequence problem, the next step is to implement the algorithm in a programming language. This involves translating the algorithm into a set of instructions that can be executed by a computer, and it involves defining the variables, functions, and control structures that are used by the algorithm.

In the case of the Fibonacci sequence problem, we have already defined a `fibonacci` function that calculates the next number in the sequence. We also have an algorithm that uses a `while` loop to iterate over the sequence of numbers and to call the `fibonacci` function to calculate each number in the sequence. To implement this algorithm in a programming language, we simply need to define the `fibonacci` function and the `while` loop in the programming language.

For example, the following code shows how to implement the Fibonacci sequence algorithm in Koala:

```javascript
// Define the fibonacci function
func fibonacci(a: int, b: int) -> int {
    // Calculate the next number in the sequence as the sum of the previous two numbers
    var c = a + b

    // Return the next number in the sequence
    return c
}

// Define the starting numbers in the sequence
var a = 0
var b = 1

// Define the number of iterations in the sequence
var n = 10

// Use a while loop to iterate over the sequence
var i = 0
while (i < n) {
    // Call the fibonacci function to calculate the next number in the sequence
    var c = fibonacci(a, b)

    // Print the next number in the sequence
    print(c)

    // Update the starting numbers in the sequence
    a = b
    b = c

    // Increment the loop counter
    i++
}
```

This code defines the `fibonacci` function and the `while` loop in Koala, and it uses these elements to implement the Fibonacci sequence algorithm. When this code is executed, it generates the first 10 numbers in the Fibonacci sequence and it prints them to the console.

Overall, implementing an algorithm in a programming language involves translating the algorithm into a set of instructions that can be executed by a computer. This involves defining the functions, variables, and control structures that are used by the algorithm, and it involves writing code that follows the steps and rules of the algorithm. By implementing the Fibonacci sequence algorithm in Koala, we have created a program that can be used to generate the Fibonacci sequence of numbers.

