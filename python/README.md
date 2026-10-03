# Python Small

[ [Home](../README.md) ]

This repository contains small Python projects and guides for beginners.

There are three markdown files that will lead you through a series of
steps to learn some beginner Python programming.

You will use the `Python interpreter` to learn about variables, functions, and classes.
**Make sure you TYPE the snippets from the markdown files into the Python interpreter**.
Not typing, doing copy/paste, will not help you learn (and is cheating at this point of the course)

## Python Setup

[ [Top](#python-small) | [Home](../README.md) ]

Make sure you have Python installed on your system:

```bash
python3 --version
```

If you don't have Python installed:
- **macOS**: Install via Homebrew: `brew install python3`

## Using the Python Interpreter

[ [Top](#python-small) | [Home](../README.md) ]

Unlike Java which requires `jshell` for interactive programming, Python is interpreted by default.

To start the Python interpreter:
```bash
python3
```

You should see the Python prompt:
```
Python 3.x.x (default, ...)
[GCC ...] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

To exit the Python interpreter:
- Type `exit()` and press Enter
- Or press `Ctrl+D` (Linux/macOS) or `Ctrl+Z` then Enter (Windows)

## Python vs Java: Key Differences

[ [Top](#python-small) | [Home](../README.md) ]

| Feature | Java | Python |
|---------|------|--------|
| Interactive Shell | `jshell` | Built-in interpreter |
| Variable Declaration | `int x = 5;` | `x = 5` |
| String Concatenation | `"Hello " + name` | `f"Hello {name}"` |
| Method Definition | `public void method() {}` | `def method():` |
| Class Constructor | `ClassName(params) {}` | `def __init__(self, params):` |
| Boolean Values | `true`, `false` | `True`, `False` |
| Code Blocks | `{ }` | Indentation |

## Learning Path

[ [Top](#python-small) | [Home](../README.md) ]

Use a browser to be able to see the markdown files.
Start with `PythonSmall.md` and follow the links to the other guides:

1. **PythonSmall.md** - Learn Python basics with the interpreter
2. **VARS.md** - Understanding Python variables and types
3. **ClassPerson.md** - Creating and using Python classes

## Tips for Success

[ [Top](#python-small) | [Home](../README.md) ]

1. **Type, don't copy-paste** - Build muscle memory
2. **Experiment freely** - Python interpreter is forgiving
3. **Use meaningful variable names** - Python encourages readability
4. **Pay attention to indentation** - Python uses whitespace for structure
5. **Read error messages** - Python error messages are helpful

## Common Python Conventions

[ [Top](#python-small) | [Home](../README.md) ]

- **Variable names**: Use `snake_case` (not `camelCase`)
- **Function names**: Use `snake_case`
- **Class names**: Use `PascalCase`
- **Constants**: Use `UPPER_CASE`
- **Indentation**: Use 4 spaces (not tabs)

## File Extensions

[ [Top](#python-small) | [Home](../README.md) ]

- **Python files**: `.py`
- **Python interactive files**: Can be saved as `.py` files

## Running Python Files

[ [Top](#python-small) | [Home](../README.md) ]

Once you create a Python file (like `hello.py`), run it with:
```bash
python3 hello.py
```

## Additional Resources

[ [Top](#python-small) | [Home](../README.md) ]

- Python official documentation: https://docs.python.org/3/
- Python tutorial: https://docs.python.org/3/tutorial/
- Learn Python the Hard Way: https://learnpythonthehardway.org/

## Getting Help

[ [Top](#python-small) | [Home](../README.md) ]

In the Python interpreter:
- `help()` - Interactive help
- `dir(object)` - Show object attributes
- `type(variable)` - Show variable type
- `help(function)` - Help for specific function

Start your Python journey with [PythonSmall.md](PythonSmall.md)!

[ [Top](#python-small) | [Next](PythonSmall.md) | [Home](../README.md) ]
