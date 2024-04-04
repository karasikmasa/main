# main
def add(x, y):
    """Function to add two numbers"""
    return x + y

def subtract(x, y):
    """Function to subtract two numbers"""
    return x - y

def multiply(x, y):
    """Function to multiply two numbers"""
    return x * y

def divide(x, y):
    """Function to divide two numbers"""
    if y == 0:
        return "Error: Division by zero!"
    else:
        return x / y

def main():
    # Getting input from the user
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    # Performing operations
    addition_result = add(num1, num2)
    subtraction_result = subtract(num1, num2)
    multiplication_result = multiply(num1, num2)
    division_result = divide(num1, num2)

    # Displaying results
    print("Addition result:", addition_result)
    print("Subtraction result:", subtraction_result)
    print("Multiplication result:", multiplication_result)
    print("Division result:", division_result)

if __name__ == "__main__":
    main()
