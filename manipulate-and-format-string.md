# Manipulate a string

## You need to display the following

```txt
first_value = '  FIRST challenge         '
second_value = '-  second challenge  -'
third_value = 'tH IR D-C HALLE NGE'

fourth_value = 'fourth'
fifth_value = 'fifth'
sixth_value = 'sixth'
```

## My code

```python
#First challenge
print(f"{first_value.title(): ^30}")

#second challenge
print(second_value.replace('-','').strip().capitalize())

#Third challenge
third_value = third_value.replace("-", "").replace(" ", "").swapcase()
third_value = (f"{third_value: >30}")
print(third_value)

#Fourth challenge
print(fourth_value, fifth_value, sixth_value, sep = "#", end = "!")

#Fifth challenge
print(f"\n \t{fourth_value}")
print(f" \t{fifth_value}")
print(f"\t{sixth_value}")
```
