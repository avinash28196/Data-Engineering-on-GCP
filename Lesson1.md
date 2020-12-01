## Writing efficient code in python.

Pythonic code is efficient 




### Print the list created by looping over the contents of names

```python
better_list = []
for name in names:
    if len(name) >= 6:
        better_list.append(name)
print(better_list)
```

### Print the list created by using list comprehension
```python
best_list = [name for name in names if len(name) >= 6]
print(best_list)
```
