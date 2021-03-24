# Functions
## DRY 
### Use cases

- What is a function and why is it useful
- How to create a function
- Function structure and arguments
- Function best practices

```python
# What is a functions
# Why functions

# How to create a function
# Syntax to create a functions: def is Python keyword that tells the interpretor that the functions is being declared

# Let's create one def name_of_the_function():
# Greeting function first iteration
# def greetings():
#     print("Welcome on board ")
# # if we run this program now there be no outcome as we have not called this function
#
# # Let's see how to call this function
# greetings()


# # Second Iteration to take the argument
# def greetings(name):
#     print("Welcome on board " + name)
# # if we run this program now there be no outcome as we have not called this function
#
# # Let's see how to call this function
# greetings("James")

# # Third Iteration - Let's create an add() to pass 2 args and adds the 2 values
# def add(num1, num2):
#     print(num1 + num2)
# add(3, 2)

# Fourth Iterations - To use return statement instead of the print()
def subtract(num1, num2):
    print("This line is before the return statement")
    return (num1 - num2) # return should be the last statement
    print("This line does not get executed ") # doesn't get executed

print(subtract(4, 2))


```