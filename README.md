# Calculator-
# how to make a calculator in different ways 
# 1st way
```python
def simple_calculator(operation):
    num1 = float(input("Enter first number: "))  # Convert string input to float
    num2 = float(input("Enter second number: "))

    if operation == 'add':
        return num1 + num2
    elif operation == 'subtract':
        return num1 - num2
    elif operation == 'multiply':
        return num1 * num2
    elif operation == 'divide':
        if (num1 / num2 == 0) and (num1/num2 !=0):
            return num1 / num2
    else:
        return "Error: Unsupported operation."

operation = input("Enter operation (add, subtract, multiply, divide): ").lower()
result = simple_calculator(operation)
print(f"The result is: {result}")


# 2nd way 
def simple_calculator(operation):
    num1 = float(input("Enter first number: "))  # Convert string input to float
    num2 = float(input("Enter second number: "))

    if operation == 'add':
        return num1 + num2
    elif operation == 'subtract':
        return num1 - num2
    elif operation == 'multiply':
        return num1 * num2
    elif operation == 'divide':
        if num2 != 0:
            return num1 / num2
        else:
            return "Error: Cannot divide by zero."
    else:
        return "Error: Unsupported operation."

operation = input("Enter operation (add, subtract, multiply, divide): ").lower()
result = simple_calculator(operation)
print(f"The result is: {result}")


# 3rd way 
def simple_calculator(operation):
    num1 = float(input("Enter first number: "))  # Convert string input to float
    num2 = float(input("Enter second number: "))

    if operation == 'add':
        return num1 + num2
    elif operation == 'subtract':
        return num1 - num2
    elif operation == 'multiply':
        return num1 * num2
    elif operation == 'divide':
        if (num1 / num2 == 0) or (num1/num2 !=0):
            return num1 / num2
    else:
        return "Error: Unsupported operation."

operation = input("Enter operation (add, subtract, multiply, divide): ")#.lower()
result = simple_calculator(operation)
print(f"The result is: {result}")


