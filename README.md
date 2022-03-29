# Python

- [Python](#python)
  - [Python Numbers](#python-numbers)
    - [Type Conversion](#type-conversion)
  - [Python Strings](#python-strings)
    - [Strings](#strings)
    - [Multiline Strings](#multiline-strings)
    - [String Methods](#string-methods)
    - [How to print a backslash in Python](#how-to-print-a-backslash-in-python)
  - [Python Operators](#python-operators)
    - [Python Arithmetic Operators](#python-arithmetic-operators)
  - [Python User Input](#python-user-input)

## Python Numbers

### Type Conversion

`int()`: convert to int  
The `int()` function converts the specified value into an integer number.

#### Syntax

`int(value, base)`

#### Parameter Values

**value**: A number or a string that can be converted into an integer number  
**base**: A number representing the number format. Default value: 10

`float()`: convert to float  
`complex()`: convert to complex  
but you cannot convert complex numbers into another number type.

## Python Strings

### Strings

Strings in python are surrounded by either single quotation marks, or double quotation marks. `'hello'` is the same as `"hello"`.

### Multiline Strings

You can assign a multiline string to a variable by using three quotes. In the result, the line breaks are inserted at the same position as in the code.

```python
a = """Hello, my name is Kaye.
Nice to meet you.
"""
a = '''You can also use this.
Yes, this is three single quotes.
'''

print("""Or You can put like this.
Of course, You can use three single quotes.
""")
```

### String Methods

`split()`: Splits the string at the specified separator, and returns a list

#### Syntax

`string.split(separator, maxsplit)`

#### Parameter Values

**separator**: optional. Specifies the separator to use when splitting the string. By default any whitespace is a separator.  
**maxsplit**: Optional. Specifies how many splits to do. Default value is -1, which is "all occurrences".

### How to print a backslash in Python

#### Use two backslashes to represent a backslash

`"\\"`

#### Use a raw string to represent a backslash

`r"abc\123"`

## Python Operators

### Python Arithmetic Operators

Arithmetic operators are used with numeric values to perform common mathematical operations.
| Operator | Name |
| -------- | ---- |
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus |
| \\\ | Exponentiation |
| // | Floor division |

## Python User Input

Python allows for user input. Also python stops executing when it comes to the `input()` function, and continues when the user has given some input.

```python
username = input("Enter username:")
print("Username is: " + username)
```
