# Build a simple calculator

## You need to display the following

`output`:

```python
Simple calculator!
First number? 4
Operation? *
Second number? 5
product of 4 * 5 equals 20
```

`If users fail to enter a numeric value:`

```python
Please input a number.
```

`If users enter an operation that isn't recognized:`

```python
Operation not recognized.
```

## My code

```python
print("Simple calculator!")
first_number = input("First number? ")

if first_number.isnumeric() == False:
    print("Please input a number.")
    exit()

operation = input("Operation? ")

second_number = input("Second number? ")
if second_number.isnumeric() == False:
    print("Please input a number.")
    exit()

first_number = int(first_number)
second_number = int(second_number)


result = 0

if operation == "+":
    print(first_number + second_number)
    label = "sum"
elif operation == "-":
    print(first_number - second_number)
    label = "rest"
elif operation == "*":
    print(first_number * second_number)
    label = "multiplication"
elif operation == "/":
    print(first_number / second_number)
    label = "quotient"
elif operation == "**":
    print(first_number ** second_number)
    label = "exponent"
elif operation == "%":
    print(first_number % second_number)
    label = "modulus"
else:
    print('Operation not recognized.')
    exit()
print( label, "of", first_number, operation, second_number, "equals", result )
```