# Chapter 3: Basic Concepts in Coding and Computational Thinking

In this chapter, we will explore some of the fundamental concepts in coding and computational thinking, which are important for building and working with computer programs. These concepts include variables, data types, operators, and control structures, which are the building blocks of any program.

## 3.1: Variables and Data Types

One of the most important concepts in coding and computational thinking is the concept of a **variable**. A variable is a named location in memory where a program can store and retrieve data. Variables are used to store and manipulate data, and they are essential for building complex and powerful programs.

In Koala, variables are declared using the `var` keyword, followed by the name of the variable, and an optional assignment operator and initial value. For example, the following code declares a variable called `x`:

```javascript
var x
```

This code creates a new variable called `x`, and it initializes the variable to the default value for its data type. In Koala, all variables have a specific **data type**, which determines the kind of data that the variable can store. Some of the most common data types in Koala include:

- `int`: An integer data type, which can store whole numbers, such as 1, 2, 3, or 4.
- `float`: A floating-point data type, which can store decimal numbers, such as 1.0, 2.5, or 3.1415.
- `string`: A string data type, which can store sequences of characters, such as "hello" or "world".
- `bool`: A Boolean data type, which can store the values `true` or `false`.

When you declare a variable, you can specify the data type of the variable using the `:` operator, followed by the data type name. For example, the following code declares a variable of type `string`:

```javascript
var message: string
```

This code creates a new variable called `message`, and it specifies that the variable is of type `string`. The variable is initialized to the default value for the `string` data type, which is the empty string.

Additionally, when you declare a variable, you can initialize it with an initial value using the `=` assignment operator. For example, the following code declares a variable of type `string` and initializes it with the value "hello":

```javascript
var message: string = "hello"
```

This code creates a new variable called `message`, and it specifies that the variable is of type `string`. The variable is initialized with the value "hello".

To declare a `bool` variable in Koala, you can use the `var` keyword, followed by the variable name, the `:` operator, and the `bool` data type name. For example, the following code declares a `bool` variable called `flag`:

```javascript
var flag: bool
```

This code creates a new variable called flag, and it specifies that the variable is of type bool. The variable is initialized to the default value for the bool data type, which is false.

Additionally, you can initialize the bool variable with a specific value using the = assignment operator. For example, the following code declares a bool variable called flag and initializes it with the value true:

```javascript
var flag: bool = true
```

This code creates a new variable called `flag`, and it specifies that the variable is of type bool. The variable is initialized with the value `true`, which is assigned to the variable using the `=` operator.

Overall, declaring a `bool` variable in Koala is a simple and straightforward process. By following the steps described above, you can create a new `bool` variable, specify its data type, and initialize it with an initial value. This allows you to store and manipulate Boolean values in your Koala programs.


## 3.2: Control Structures and Conditional Statements

In addition to variables and data types, another important concept in coding and computational thinking is the concept of a **control structure**. A control structure is a block of code that defines how the program should flow and execute, and it allows the program to make decisions and to perform different actions based on different conditions.

In Koala, control structures are defined using **conditional statements**, which are statements that evaluate a condition and determine whether a block of code should be executed or not. Some of the most common conditional statements in Koala include:

- `if`: An `if` statement evaluates a condition, and it executes a block of code if the condition is `true`. For example:

```javascript
if (x > 0) {
    // This code is executed if x is greater than 0
}
```

- `else`: An `else` statement is used in combination with an `if` statement, and it defines a block of code that is executed if the condition of the `if` statement is `false`. For example:


```javascript
if (x > 0) {
    // This code is executed if x is greater than 0
} 
else {
    // This code is executed if x is not greater than 0
}
```


- `else if`: An `else if` statement is similar to an `else` statement, but it allows you to define multiple conditions and blocks of code that are executed based on the conditions. For example:

```javascript
if (x > 0) {
    // This code is executed if x is greater than 0
} 
else if (x == 0) {
    // This code is executed if x is equal to 0
} 
else {
    // This code is executed if x is less than 0
}
```


In addition to these basic conditional statements, Koala also provides other control structures, such as `switch` statements, `for` loops, and `while` loops, which allow you to define more complex and sophisticated control flow in your programs.

Overall, control structures and conditional statements are an important concept in coding and computational thinking, and they are essential for building powerful and flexible programs. By using these constructs, you can define the flow and execution of your programs, and you can make decisions and perform different actions based on different conditions.


## 3.3: Loops and Iteration

In addition to control structures and conditional statements, another important concept in coding and computational thinking is the concept of **loops and iteration**. Loops and iteration are used to perform a block of code multiple times, based on a specific condition or set of conditions.

In Koala, loops and iteration are implemented using **loop statements**, which are statements that allow you to define a block of code that is repeated multiple times. Some of the most common loop statements in Koala include:

- `for`: A `for` loop is used to iterate over a sequence of values, such as a list or an array. For example:

```javascript
for (var i = 0; i < 10; i++) {
    // This code is executed 10 times, starting at 0 and ending at 9
}
```

- `while`: A `while` loop is used to repeat a block of code while a specific condition is `true`. For example:

```javascript
while (x > 0) {
    // This code is executed while x is greater than 0
}
```


- `do-while`: A `do-while` loop is similar to a `while` loop, but it guarantees that the code is executed at least once, even if the condition is `false` at the start. For example:

```javascript
do {
    // This code is executed at least once, and it is repeated while x is greater than 0
} while (x > 0)
```

In addition to these basic loop statements, Koala also provides other constructs and mechanisms that support loops and iteration, such as the `break` and `continue` keywords, which allow you to control the flow and execution of a loop.

The `break` and `continue` keywords are used to control the flow and execution of a loop in Koala. The break keyword is used to immediately exit a loop, and the continue keyword is used to skip the remaining code in the current iteration of the loop and move to the next iteration.

For example, consider the following code that uses a `for` loop to iterate over a list of numbers:

```javascript
var numbers = [1, 2, 3, 4, 5]

for (var i = 0; i < numbers.length; i++) {
    // Print the current number
    print(numbers[i])

    // Check if the current number is equal to 3
    if (numbers[i] == 3) {
        // If the number is 3, exit the loop
        break
    }
}
```

In this code, the `for` loop iterates over a list of numbers, and it prints each number in the list. Inside the loop, there is an `if` statement that checks if the current number is equal to 3. If the number is 3, the `break` keyword is used to immediately exit the loop.

As a result, the `for` loop will only iterate over the first three numbers in the list, and it will not print the number 4 or 5. This is because the `break` keyword is used to exit the loop when the number 3 is encountered, which means that the remaining iterations are skipped.

Similarly, the `continue` keyword can be used to skip the remaining code in the current iteration of a loop, and to move to the next iteration. For example, consider the following code that uses a `while` loop to iterate over a list of numbers:

```javascript
var numbers = [1, 2, 3, 4, 5]
var i = 0

while (i < numbers.length) {
    // Check if the current number is equal to 3
    if (numbers[i] == 3) {
        // If the number is 3, skip the remaining code and move to the next iteration
        i++
        continue
    }

    // Print the current number
    print(numbers[i])

    // Move to the next iteration
    i++
}
```

In this code, the while loop iterates over a list of numbers, and it checks if the current number is equal to 3. If the number is 3, the continue keyword is used to skip the remaining code in the current iteration and to move to the next iteration.

As a result, the while loop will iterate over all numbers in the list, but it will not print the number 3. This is because the continue keyword is used to skip the printing of the number 3, and to move to the next iteration of the loop.

Overall, the break and continue keywords are useful tools for controlling the flow and execution of a loop in Koala. By using these keywords, you can exit a loop early, or you can skip the remaining code in the current iteration of a loop and move to the next iteration. This allows you to define complex and flexible control flow in your programs.


## 3.4: Functions and Procedures

In addition to loops and iteration, another important concept in coding and computational thinking is the concept of **functions and procedures**. Functions and procedures are blocks of code that can be invoked and executed multiple times, and they allow you to define and reuse code in a modular and organized way.

In Koala, functions and procedures are defined using the `func` keyword, followed by the function name, a list of parameters, and the block of code that makes up the function body. For example, the following code defines a function called `print_hello` that takes no parameters and simply prints the string "Hello, world!":

```javascript
func print_hello() {
    print("Hello, world!")
}
```


To invoke or call a function, you simply use the function name followed by a pair of parentheses, and you can pass any necessary arguments or parameters to the function inside the parentheses. For example, the following code invokes the `print_hello` function defined above:

```javascript
print_hello()
```


When this code is executed, the `print_hello` function is called, and it prints the string "Hello, world!" to the console.

In addition to defining functions that take no parameters, you can also define functions that take one or more parameters. For example, the following code defines a function called `print_number` that takes a single `int` parameter called `n`:

```javascript
func print_number(n: int) {
    print(n)
}
```


To call this function and pass a value to the `n` parameter, you simply use the function name followed by the value you want to pass to the parameter inside the parentheses. For example, the following code invokes the `print_number` function with the value `42`:


```javascript
print_number(42)
```

When this code is executed, the `print_number` function is called, and it prints the value `42` to the console.

Overall, functions and procedures are an important concept in coding and computational thinking, and they are essential for building modular and organized programs. By using functions and procedures, you can define blocks of code that can be invoked and executed multiple times, and you can pass parameters and arguments to these functions to customize their behavior. This allows you to reuse and modularize your code, and to write programs that are more flexible and maintainable.

