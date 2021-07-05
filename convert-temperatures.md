# Convert temperatures from Fahrenheit to Celsius

The mathematical formula for converting a temperature measured in Fahrenheit to a temperature measured in Celsius is shown in the following code:

```python
celsius = (fahrenheit - 32) * 5/9
```

## You need to display the following:

```python
What is the temperature in fahrenheit?  55
Temperature in celsius is 12

```

```python
What is the temperature in fahrenheit?  bob
Input is not a number.
```

## The code

```python
fahrenheit = input("What is the temperature in Fahrenheit? ")

if fahrenheit.isnumeric() == False:
    print("Input is not a number.")
    exit()

fahrenheit = int(fahrenheit)

celsius = int((fahrenheit - 32) * 5/9)
print("Temperature in celsius is " + str(celsius))
```

## Additional to practice

```python
fahrenheit = input(("What is the temperature in fahrenheit? "))
if fahrenheit.isnumeric() == False:
    print("Input is not a number.")

fahrenheit = int(fahrenheit)

celsius = int((fahrenheit - 32) * 5/9)
print("Temperature in celsius is", celsius)
```
