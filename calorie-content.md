# Calorie content

## You need to display the following

```tex
Today's date?
December 7th, 2020
Breakfast calories?
250
Lunch calories?
300
Dinner calories?
500
Snack calories?
150
Calorie content for December 7th, 2020: 1200
```

## My code

```python
date = input("Today's date?: \n")
Breakfast = int(input("Breakfast calories? \n"))
lunch = int(input("Lunch calories? \n"))
dinner = int(input("Dinner calories? \n"))
snack = int(input("Snack calories? \n"))
calories = int(Breakfast + lunch + dinner + snack)

print("Calorie content for " , date , ":", calories)
```

## Reference

[Exercise](https://docs.microsoft.com/en-us/learn/modules/python-create-first/5-challenge)
