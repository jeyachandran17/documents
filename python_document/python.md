## Python

<hr>

### What is python ?

1. Python is a popular programming,
2. It was create by Guido van Rossum and released in 1991.
3. It's used for
    - web development (server-side),
    - software development,
    - mathematics,
    - system scripting.

<hr>

### What can Python do?
1. Python can be used on a server to create web applications.
2. Python can be used alongside software to create workflows.
3. Python can connect to database systems. It can also read and modify files.
4. Python can be used to handle big data and perform complex mathematics.
5. Python can be used for rapid prototyping, or for production-ready software development.

<hr>

### Why Python?
1. Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
2. Python has a simple syntax similar to the English language.
3. Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
4. Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
5. Python can be treated in a procedural way, an object-oriented way or a functional way.

<hr>

### Python comments

1. Comments can be used to explain Python code.
2. Comments can be used to make the code more readable.
3. Comments can be used to prevent execution when testing code.
4. comments start with a `#` and python will ignore them
5. the single comments is used to `#` or mulitple comments is used to`"""  """`

- Example:
```
# This is a single comment
```

```
"""
This is a comment
written in
more than just one line 
"""
```
<hr>

### Python variable

- Variables are containers for storing data values.

- Creating Variables
    - Python has no command for declaring a variable.
    - A variable is created the moment you first assign a value to it.
- Example : 
```
x = 5   # type of int 
y = "5"   # type of str 
z = 5.0   # type of float 
```

<hr>

### Rule for Variable Name declear

1. A variable can have a short name (like x and y) or a more descriptive name (name, age, total_volume). 
2. Rules for Python variables:
    - A variable name must start with a letter or the underscore character
    - A variable name cannot start with a number
    - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
    - Variable names are case-sensitive (age, Age and AGE are three different variables)
    - A variable name cannot be any of the Python keywords.

- Example :
```
variablename = "value"
variable_name = "value"
_variable_name = "value"
variableName = "value"
VARIABLENAME = "value"
variablename2 = "value"
```
<hr>

### Python variable - asign multiple values

- Python allows you to assign values to multiple variables in one line
- Example : 
```
language, year, creator = "Python", 1991, "Guido van Rossum" 
print(language)
print(year)
print(creator)
```
<hr>

### Asign One Value to Multiple Variables
- And you can assign the same value to multiple variables in one line:

- Example :
``` 
x = y = z = "Hello World"
print(x)
print(y)
print(z)
```

<hr>

### Global variable

1. Variables that are created outside of a function (as in all of the examples above) are known as global variables.

2. Global variables can be used by everyone, both inside of functions and outside.
- Example :
```
x = "hello world"

def my_function(){
    print(x)
}

my_function()
```
3. To create a global variable inside a function, you can use the `global` keyword.
- Example :
```
def my_function():
  global x
  x = "hello world"

my_function()

print(x)
```
<hr>

### Data types

1. Variables can store data of different types, and different types can do different things.

2. Python has the following data types built-in by default, in these categories:

    - Text Type:	
        - str
    - Numeric Types:	
        - int
        - float 
        - complex
    - Sequence Types:	
        - list 
        - tuple 
        - range
    - Mapping Type:	
        - dict
    - Set Types:	
        - set
        - frozenset
    - Boolean Type:	
        - bool
    - Binary Types:	
        - bytes 
        - bytearray 
        - memoryview
    - None Type:	
        - NoneType

<hr>

### get data type

- You can get the data type of any object by using the type() function

- Example : 
```
x = "hello world" # x is a string type
print(type(x))  # this output <class 'str'>
```
<hr>