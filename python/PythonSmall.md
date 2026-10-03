# PythonSmall

[ [Home](../README.md) ]

simple python exercises using the Python interpreter

## Lab Brief <!-- omit from toc -->

[ [Top](#pythonsmall) | [Home](../README.md) ]

Learn to use the Python interpreter to run Python code.

- [PythonSmall](#pythonsmall)
  - [Steps](#steps)
    - [Startup the Python interpreter](#startup-the-python-interpreter)
  - [Section 0](#section-0)
  - [Section 1](#section-1)
  - [Section 2](#section-2)
  - [Let's talk about odd and even numbers](#lets-talk-about-odd-and-even-numbers)
  - [Ok, enough here](#ok-enough-here)

## Steps

[ [Top](#pythonsmall) | [Home](../README.md) ]

### Startup the Python interpreter

[ [Top](#pythonsmall) | [Back](#steps) | [Home](../README.md) ]

1. Open a terminal
2. Type `python3` or `python`
3. Type `print("Hello, World!")`
4. Type `x = 5`
5. Type `x`
6. Type `x + 5`
7. Type `x`
8. Type `x = x + 10`
9. Type `x`
10. Type `def println(s): print(s)`
11. Type `println("your name here!")`

Let's save this to a file. Exit the Python interpreter with `exit()` or `Ctrl-D`.

Create a file called `hello_world.py`:

```python
print("Hello, World!")
x = 5
print(x)
print(x + 5)
print(x)
x = x + 10
print(x)

def println(s):
    print(s)

println("your name here!")
```

Run it with: `python3 hello_world.py`

## Section 0

[ [Top](#pythonsmall) | [Home](../README.md) ]

**In the steps below, you will be using the Python interpreter to run Python code.**

**Start training your brain by TYPING the code into the Python interpreter. DO NOT COPY AND PASTE.**

**CopyPasta is the enemy of learning. It's cheating yourself. And at this point, it's cheating in this course.**

### Using the Python interpreter to run a simple Python program<!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-0) | [Home](../README.md) ]

Start the Python interpreter and type the following code:

Let's use a simple while loop to print out the numbers from 1 to 10.

```python
i = 1
while i <= 10:
    print(i)
    i += 1
```

Now TYPE it into the Python interpreter. Notice how Python uses indentation instead of braces.

## Section 1

[ [Top](#pythonsmall) | [Home](../README.md) ]

### Using the Python interpreter to run a simple Python program with a function <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

A function in Python is a block of code that performs a specific task.
You use functions so you don't have to write the same code over and over again.
(Programmers like to be lazy and efficient that way.)

Let's create a simple function to print out the numbers from 1 to 10.

```python
def print_numbers():
    i = 1
    while i <= 10:
        print(i)
        i += 1
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `print_numbers()` and then pressing Enter.

### Using the Python interpreter to run a simple Python program with a function that takes a parameter <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Let's use a simple function to print out the numbers from 1 to `n`.

```python
def print_numbers(n):
    i = 1
    while i <= n:
        print(i)
        i += 1
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `print_numbers(5)` and then pressing Enter.
and then `print_numbers(10)` and then pressing Enter.
and then `print_numbers(20)` and then pressing Enter.

### Using the Python interpreter to run a simple Python program with a function that takes a parameter and returns a value <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Let's use a simple function to return the sum of the numbers from 1 to `n`.

```python
def sum_numbers(n):
    i = 1
    total = 0
    while i <= n:
        total = total + i
        i += 1
    return total
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `sum_numbers(5)` and then pressing Enter.
and then `sum_numbers(11)` and then pressing Enter.
and then `sum_numbers(23)` and then pressing Enter.
and then `sum_numbers(5683)` and then pressing Enter.
and then `sum_numbers(106839)` and then pressing Enter.

### Using the Python interpreter to run a simple Python program with a function that uses a for loop <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Let's use a simple function to return the sum of the numbers from 1 to `n`.

```python
def sum_numbers(n):
    total = 0
    for i in range(1, n + 1):
        total = total + i
    return total
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `sum_numbers(5)` and then pressing Enter.
and then `sum_numbers(10)` and then pressing Enter.
and then `sum_numbers(20)` and then pressing Enter.
and then `sum_numbers(106839)` and then pressing Enter.

### Using the Python interpreter to run a simple Python program with a function that calls another function <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Let's use a simple function to return the sum of the numbers from 1 to `n`.

```python
def sum_numbers(n):
    total = 0
    for i in range(1, n + 1):
        total = total + i
    return total

def sum_numbers_to_10():
    return sum_numbers(10)
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `sum_numbers_to_10()` and then pressing Enter.

### Save your Python code to a file <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Exit the Python interpreter and create a file called `sum_numbers.py`:

```python
def sum_numbers(n):
    total = 0
    for i in range(1, n + 1):
        total = total + i
    return total

def sum_numbers_to_10():
    return sum_numbers(10)

def sum_numbers_to_13():
    return sum_numbers(13)

if __name__ == "__main__":
    print(sum_numbers_to_10())
    print(sum_numbers_to_13())
```

Run it with: `python3 sum_numbers.py`

### Write a few functions that take parameters and return values <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-1) | [Home](../README.md) ]

Write a function that takes parameters and returns a value.

```python
def add_two_numbers(x, y):
    return 0  # fix this
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `add_two_numbers(5, 10)` and then pressing Enter.
Notice how the answer is wrong. Fix the function and run it again.

Now create 3 functions that take two parameters and return a math operation of the two numbers.

1. divide `divide_two_numbers(x, y)`
2. multiply `multiply_two_numbers(x, y)`
3. subtract `subtract_two_numbers(x, y)`

## Section 2

[ [Top](#pythonsmall) | [Home](../README.md) ]

Let's do some functions with if statements.

### Write a function that takes a parameter and returns a value <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-2) | [Home](../README.md) ]

Write a function that takes a parameter and returns a value.

```python
def is_even(x):
    return 0  # fix this
```

Now TYPE it into the Python interpreter.

and **call** the function by typing `is_even(5)` and then pressing Enter.

Notice how the answer is wrong. Fix the function and then run it again.
(what might be wrong with the function?) maybe `if` the number is even, return `1`, otherwise return `0`.

But, what if we want to return a `boolean` instead of an `int`?

### Write a function that takes a parameter and returns a boolean <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-2) | [Home](../README.md) ]

Write a function that takes a parameter and returns a boolean.

```python
def is_even(x):
    return False  # fix this
```

Now TYPE it into the Python interpreter.

and **call** the function by typing `is_even(5)` and then pressing Enter.
So... what's wrong with the function? maybe `if` the number is even, return `True`, otherwise return `False`.

### Write a function that takes a parameter and returns a boolean <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#section-2) | [Home](../README.md) ]

Write a function that takes a parameter and returns a boolean.

```python
def is_odd(x):
    return False  # fix this
```

Now TYPE it into the Python interpreter.
and **call** the function by typing `is_odd(5)` and then pressing Enter.

## Let's talk about odd and even numbers

[ [Top](#pythonsmall) | [Home](../README.md) ]

How can we tell if a number is odd or even? The most common way is to use the modulo operator `%`.

See how it works:

```python
x = 5
y = 2
x % y
```

What does it return? What does it mean?

now write a while loop that prints out the numbers from 1 to 10 and prints out the modulo of each number with 2.

```python
i = 1
while i <= 10:
    print(f"{i} % 2 = {i % 2}")
    i += 1
```

Now TYPE it into the Python interpreter.

Hmm. It appears that the `%` (mod or modulo) operator returns `0` if the number is even and `1` if the number is odd.

How can we use that in is_even and is_odd functions?

### Write is_odd and is_even functions using the modulo operator <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#lets-talk-about-odd-and-even-numbers) | [Home](../README.md) ]

You'll need an if statement to check if the number is even or odd.

```python
def is_even(x):
    return x % 2 == 0
```

And now you write the is_odd function. Remember `!=` means "not equal to".

You could also use `==` and make the 0 a 1, right?

### Write a function that prints "odd" or "even" for the numbers from 1 to 10 <!-- omit from toc -->

[ [Top](#pythonsmall) | [Back](#lets-talk-about-odd-and-even-numbers) | [Home](../README.md) ]

Write a function that prints "odd" or "even" for the numbers from 1 to 10.

```python
def print_odd_even():
    i = 1
    while i <= 10:
        if is_even(i):
            print(f"{i} is even")
        else:
            print(f"{i} is odd")
        i += 1
```

see the `else` part? what if you remove it?
(puzzle over it in your mind. c'mon experiment!)

Now TYPE it into the Python interpreter.

## Ok, enough here

[ [Top](#pythonsmall) | [Home](../README.md) ]

You've done a lot of work. You've learned a lot about the Python interpreter and Python functions.
Make sure you save it all to github.

```bash
git add .
git commit -m "done with Python interpreter and PythonSmall"
git push
```

Now, switch to [VARS.md](VARS.md) and learn about variables in Python.

[ [Top](#pythonsmall) | [Next](VARS.md) | [Home](../README.md) ]