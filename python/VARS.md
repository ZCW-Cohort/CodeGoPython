# Python Variables Guide: A Beginner's Tutorial

[ [Home](../README.md) ]

This guide will help you understand different variable types in
Python using the Python interpreter environment.
We'll explore int, bool, float, and str variables
with practical examples.

## Getting Started with the Python interpreter

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

To begin:
1. Open your terminal/command prompt
2. Type `python3` (or `python`) and press Enter
3. You should see the Python prompt: `>>>`

## Integer (int) Variables

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

**Definition:** An integer variable stores whole numbers without decimal points.

**How to declare:**
```python
variable_name = value
```

**TYPE into Python interpreter:**
```python
>>> age = 25
>>> age
25

>>> score = 100
>>> score
100

>>> negative = -10
>>> negative
-10

>>> sum_total = age + score
>>> sum_total
125
```

Type `dir()` to see all variables in your current namespace, or use `globals()` to see global variables.

### Save your work

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

Save the work in a file called `vars.py`.

```python
# Exit Python interpreter with exit() or Ctrl-D
# Create a file vars.py with your variable examples

age = 25
score = 100
negative = -10
sum_total = age + score

print(f"Age: {age}")
print(f"Score: {score}")
print(f"Sum: {sum_total}")
```

Now, save the repo to your GitHub account.

```bash
git add .
git commit -m "Add Python Variables Guide"
git push
```

Go to a browser and navigate to your GitHub account to see the changes in this repository.

Okay go back to the terminal and let's continue.

## Boolean Variables

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

**Definition:** A boolean variable stores True/False values.

**How to declare:**
```python
variable_name = True/False
```

**TYPE into Python interpreter:**
```python
>>> is_student = True
>>> is_student
True

>>> has_passed_exam = False
>>> has_passed_exam
False

>>> result = 10 > 5
>>> result
True

>>> is_equal = (15 == 15)
>>> is_equal
True
```

## Float Variables

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

**Definition:** A float variable stores decimal numbers with precision.

**How to declare:**
```python
variable_name = value
```

**TYPE into Python interpreter:**
```python
>>> price = 19.99
>>> price
19.99

>>> temperature = -2.5
>>> temperature
-2.5

>>> result = 10.5 + 3.7
>>> result
14.2

>>> division = 10.0 / 3.0
>>> division
3.3333333333333335
```

## String Variables

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

**Definition:** A string variable stores text (sequence of characters).

**How to declare:**
```python
variable_name = "text"
variable_name = 'text'
```

Hey, here, replace "John" with your name.

**TYPE into Python interpreter:**
```python
>>> name = "John"
>>> name
'John'

>>> greeting = "Hello, World!"
>>> greeting
'Hello, World!'

>>> combined = name + " says " + greeting
>>> combined
'John says Hello, World!'

>>> empty = ""
>>> empty
''

>>> formatted = f"{name} says {greeting}"
>>> formatted
'John says Hello, World!'
```

## Python Dynamic Typing

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

Unlike Java, Python variables don't need type declarations. Python figures out the type automatically:

```python
>>> x = 5          # x is an int
>>> type(x)
<class 'int'>

>>> x = "hello"    # now x is a string
>>> type(x)
<class 'str'>

>>> x = 3.14       # now x is a float
>>> type(x)
<class 'float'>
```

## Practice Tips

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

1. Try typing these examples in the Python interpreter
2. Experiment with different values
3. Try combining variables in operations
4. Use `type(variable)` to check the type of any variable
5. Use `dir()` or `globals()` to see all variables
6. Save your work in Python files (.py extension)
7. Use `exit()` to leave the Python interpreter

Be sure to do commit of all this work to your GitHub repository.

```bash
git add .
git commit -m "Add Python Variables Guide"
git push
```

## Common Python Features

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

- **Dynamic typing**: No need to declare variable types
- **Snake_case**: Python uses snake_case for variable names (not camelCase)
- **f-strings**: Use f"text {variable}" for string formatting
- **Multiple assignment**: `x, y = 1, 2`
- **Type checking**: Use `type(variable)` to check types

## Common Mistakes to Avoid

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Home](../README.md) ]

- Don't forget that Python is case-sensitive
- Remember that strings can use single or double quotes
- Python uses `True`/`False` (capitalized) not `true`/`false`
- Use snake_case for variable names in Python
- Remember that variables are dynamically typed

This guide should give you a solid foundation for understanding and working with basic Python variables in the interpreter. Practice with these examples and try creating your own variables to become more comfortable with these concepts.

Now go to the [ClassPerson.md](ClassPerson.md) guide to learn about creating custom classes in Python.

[ [Top](#python-variables-guide-a-beginners-tutorial) | [Next](ClassPerson.md) | [Home](../README.md) ]
