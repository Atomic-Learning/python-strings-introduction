# Creating Strings

In Python, you can create a string by putting text between quotation marks. Python accepts both single quotes (`'`{.python}) and double quotes (`"`{.python}):

```py-cell
greeting = "Hello world"
name = 'Alice'

print(greeting)
print(name)
```

Some style guides recommend using one type of quote consistently (e.g., always double quotes), but Python itself doesn't enforce this. The key is to be consistent within your codebase.

# Empty Strings

A string can be empty—containing zero characters:

```py-cell
empty = ""
print(empty) # No text will be displayed because the string is empty
```

# Valid Characters in Strings

Strings in Python can contain any valid Unicode characters, including letters, numbers, punctuation, and even emojis:

```py-cell
exotic_string = ":@123😀🎉"
print(exotic_string)
```

Some characters may require special handling (such as newlines or tabs), but in general, you can include any character you want in a string.
