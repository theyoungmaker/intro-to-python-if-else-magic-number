# Solution

```python
number = int(input())

is_special_magic_number = number % 3 == 0 and number % 5 == 0
is_magic_number = number % 3 == 0 or number % 5 == 0 or number % 7 == 0

if (is_special_magic_number):
    print("Abracadabra")
elif (is_magic_number):
    print("Magic Number")
else:
    print("Not Magic Number")

```
  