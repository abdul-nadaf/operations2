try:
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))

    print(f"Addition: {a + b}")
    print(f"Subtraction: {a - b}")
    print(f"Multiplication: {a * b}")
    
    # Handling division separately to catch division by zero
    if b != 0:
        print(f"Division: {a / b}")
    else:
        print("Division: Cannot divide by zero.")

except ValueError:
    print("Please enter valid numbers.")
