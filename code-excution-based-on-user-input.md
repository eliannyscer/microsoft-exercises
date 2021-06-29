# Code execution based on user input

## What i need to do?

```tex
Would you like to continue? no
Exiting

Would you like to continue? yes
Continuing ...
Complete!

Would you like to continue? bob 
Please try again and respond with yes or no.
```

## My code

```python
user = input("Would you like to continue: ")
if user == "yes" or user == "y" :
    print("Continuing...", "\nComplete!")
elif user == "no" or user == "n":
    print("Exiting!")
else:
    print("Please try again and response with yes or not.")
```

## Reference

[Exercise](https://docs.microsoft.com/en-us/learn/modules/python-if-elif-else/4-challenge)

