# Challenge - Guess a number

## you need to display the following

`Exercise number 1:`

```python
Guess a number between 1 and 5: 3
Guess a number between 1 and 5: 4
You guessed it in 2 tries!
```

The user enters strings that can't be converted to numbers, but the program keeps running and keeps tallying the number of guesses.

```python
Guess a number between 1 and 5: Beth
Guess a number between 1 and 5: Ellie
Guess a number between 1 and 5: 3
Guess a number between 1 and 5: 4
Guess a number between 1 and 5: 2
You guessed it in 5 tries!
```

## The code

```python
import random

value = random.randint(1, 5)
count = 0
guess = 0
while guess != value:
    count += 1
    guess = input('Guess a number between 1 and 5: ')
    if guess.isnumeric():
        guess = int(guess)
else:
    print(f"You guessed it in {count} tries!")
```

`Exercise number 1:`

```python
Guess a number between 1 and 10
Enter guess #1: 5
Your guess is too low, try again!
Enter guess #2: 8
Your guess is too high, try again!
Enter guess #3: 7
Your guess is too high, try again!
Enter guess #4: 6
You guessed it in 4 tries!
```

## reference

[Exercise-1](https://docs.microsoft.com/en-us/learn/modules/python-while/4-challenge)

[Exercise-2](https://docs.microsoft.com/en-us/learn/modules/python-while/6-challenge-2)
