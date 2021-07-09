# Challenge - Deal a deck of cards

## You need to display the following

```python
There are 52 cards in the deck.
Dealing ...
There are 47 cards in the deck.
Player has the following cards in their hand:
['Jack of Hearts', 'Queen of Hearts', '4 of Spades', 'Ace of Hearts', '9 of Diamonds']
```

## My code

```python
import random

cards = ["Hearts", "Spades", "Diamonds", "Clubs"]
numbers = [2, 3, 4, 5, 6, 7, 8, 9, 10, "Jack", "Queen", "King", "Ace"]
combination = len(str(numbers))
print(f"There is {combination} cards in the deck.")
print("Dealing...")

cards_choice = random.choice(cards)
numbers_choice = random.choice(numbers)

cards_choice1 = random.choice(cards)
numbers_choice1 = random.choice(numbers)

cards_choice2 = random.choice(cards)
numbers_choice2 = random.choice(numbers)

cards_choice3 = random.choice(cards)
numbers_choice3 = random.choice(numbers)



print("Player has the following cards in their hand:")
print(f"{cards_choice} of {numbers_choice},{cards_choice1} of {numbers_choice1}, {cards_choice2} of {numbers_choice2}, {cards_choice3} of {numbers_choice3}" )
```
