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

### python type casting

- Casting in python is therefore done using constructor functions:

    - int() - constructs an integer number from an integer literal, a float literal, or a string literal
    - float() - constructs a float number from an integer literal, a float literal or a string literal.
    - str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

- Example :
```
x = int(1)  # x will be 1
y = float(1) # y will be 1.0   
z = str(1)  # z will be '1'
```
<hr>

### Strings
- Strings in python are surrounded by either `single quotation marks('')`, or `double quotation marks("")`.

- `'hello'` is the same as `"hello"`.

<hr>

### Assign String to a Variable
- Assigning a string to a variable is done with the variable name followed by an equal sign and the string

- Example :
```
x = "hello"
y = 'hello'
print(x,y) # output will be hello hello
```
<hr>

### Multiline Strings
- You can assign a multiline string to a variable by using `three quotes(""" write a content """ (or) ''' write a content '''')`

- Example :
```
x = """Python is a popular programming,
It's a high level programming language,
It was create by Guido van Rossum and released in 1991.
""" 
print(x)
```
<hr>

### String Length

1. To get the length of a string, use the len() function.
2. The `len()` function returns the length of a string

- Example
```
x = "Hello, World!"
print(len(x)) # output will be 13
```
<hr>

### Check String or Not
- To check if a certain phrase or character is `present` in a string, we can use the keyword `in`.

To check if a certain phrase or character is `NOT present` in a string, we can use the keyword `not in`.

- Example for `in`
```
# Check if "python" is present in the following text

text = "welcome to learn python"
print("python" in text) # output will be "True"
```

- Example for `not in`
```
# heck if "javascript" is NOT present in the following text

text = "welcome to learn python"
print("javascript" not in text) # output will be "True"
```

<hr>

### String Slicing
1. You can return a range of characters by using the slice syntax.

2. Specify the `start index` and the `end index`, separated by a `colon(:)`, to return a part of the string.

- Example :
```
# Get the characters from position 2("2" is start position) to position 5 ("5" is end position and it's not including).

b = "welcome to python!"
print(b[2:5]) # output will be "lco"
```
<hr>

### Slicing form the Start

- By leaving out the `start index`, the range will start at first character

- Example :
```
# Get the character from the start to position 5(the 5th position not included )

x = "welcome to python!"
print(x[:5])    # output will be "welco"
```

### Slicing to the End 

- By leaving out the `End index`, the range will go to the end

- Example :
```
# The get character start from position 2, and all way ti the end

x = "welcome to python!"
print(x[2:])    # output will be "lcome to python!" 
```
<hr>

### Modify String

- Python has a setof build-n methods that you can use on string

### Upper Case

- The `upper()` method returns the string in upper case
- Example :
```
x = "welcome to python!"
print(x.upper()) # output will be "WELCOME TO PYTHON!"
```
### Lower Case

- The `lower()` method returns the string in lower case
- Example :
```
x = "WELCOME TO PYTHON!"
print(x.lower())    # output will be "welcome to python!"
```

### Remove Whitespace 

- The use to `strip()` method removes any whitespace from the beginning to the end

- Example :
```
x = " python "
print(x.strip())   # now output will be 'python'
```

### Split String
- The `split()` method returns a list, where the text between the specified separator becomes the list items 

- Example :
```
x = "welcome to python"
print(x.split(" ")) # output will be "['welcome','to','python']"  
```
<hr>