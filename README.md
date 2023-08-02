# shared-pieces
## Blue formatter
Here's some unformatted Python code that you can use to demonstrate how the Black or Blue formatter can format it:
```
def    example_function(   parameter1,parameter2  ):
    if(parameter1   and parameter2 ):
        print(   "Both parameters are true."   )
    else:
        print("At least one parameter is false.")

def   calculate_total(item1,  item2, item3,   discount   ):
    total = item1 +item2+item3
    final_total = total - discount
    return final_total

```
## Mypy
Here's an example of Python code with some typing warnings and errors that you can use to demonstrate how mypy works:

```
def greet(name: str) -> str:
    return "Hello, " + name

result = greet(5)  # This will cause a type error

numbers = [1, 2, 3, "four", 5]  # This list contains a mix of integers and a string

for num in numbers:
    print(num + 1)  # This will cause a type error for the string concatenation

def divide(a: int, b: int) -> float:
    return a / b

result = divide(10, 0)  # This will cause a division by zero error
```

Here's an example of Python code with some linting warnings and errors that you can use to demonstrate how Pylint works:
```
def example_function():
    x = 10
    y = 20
    print(x, y)
    
example_function()

def unused_variable():
    unused_var = "This variable is unused"
    
unused_variable()

def multiple_blank_lines():
    result = 5
    
    
    
    return result

multiple_blank_lines()

a = 5
b = 3
c = a+b
print(c)

print("Hello World")

```
