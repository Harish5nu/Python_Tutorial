# Python basic:

## Python Comments:

1. Single Line Comments
    
    ```python
    #This is a comment
    print("Hello, World!")
    ```
    
2. Multiline Comments
    
    ```python
    """
    This is a comment
    written in
    more than just one line
    """
    print("Hello, World!")
    ```
    

## Python Variables:

### Variables:

1. Creating Variables
    
    ```python
    x = 5 # x is of type int
    y = "John" # y is of type str
    print(x) 
    print(y)
    ```
    
2. Casting
    
    ```python
    x = str(3)    # x will be '3'
    y = int(3)    # y will be 3
    z = float(3)  # z will be 3.0
    ```
    
3. Get The Type
    
    ```python
    x = 5
    y = "John"
    print(type(x))
    print(type(y))
    ```
    
4. Single and Double Quotes
    
    ```python
    x = "John"
    # is the same as
    x = 'John'
    ```
    
5. Case-Sensitive
    
    ```python
    a = 4
    A = "Sally"
    #A will not overwrite a
    ```
    
6. Variable Names
    
    ```python
    # Legal variable names:
    myvar = "John"
    my_var = "John"
    _my_var = "John"
    myVar = "John"
    MYVAR = "John"
    myvar2 = "John"
    
    # Ilegal variable names:
    2myvar = "John"
    my-var = "John"
    my var = "John"
    ```
    
7. **Multi Words Variable Names**
    
    ```python
    # Camel Case
    # Each word, except the first, starts with a capital letter:
    myVariableName = "John"
    
    # Pascal Case
    # Each word starts with a capital letter:
    MyVariableName = "John"
    
    # Snake Case
    # Each word is separated by an underscore character:
    my_variable_name = "John"
    ```
    
8. Assign Multiple Values
    
    ```python
    # Many Values to Multiple Variables
    x, y, z = "Orange", "Banana", "Cherry"
    print(x)
    print(y)
    print(z)
    
    # One Value to Multiple Variables
    x = y = z = "Orange"
    print(x)
    print(y)
    print(z)
    
    # Unpack a Collection
    fruits = ["apple", "banana", "cherry"]
    x, y, z = fruits
    print(x)
    print(y)
    print(z)
    ```
    
9. Output Variables
    
    ```python
    x = "Python"
    y = "is"
    z = "awesome"
    print(x, y, z) # you output multiple variables, Separated by a comma
    print(x + y + z) # also use the + operator to output Multiple variables
    
    ```
    
10. Global Variables
    
    ```python
    # Without using global variable
    x = "awesome"
    
    def myfunc():
      x = "fantastic"
      print("Python is " + x)
    
    myfunc()
    
    print("Python is " + x)
    
    # Using Global Variable
    x = "awesome"
    
    def myfunc():
      global x
      x = "fantastic"
    
    myfunc()
    
    print("Python is " + x)
    ```
