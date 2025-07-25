# print square
```
def print_squares(n):
    for i in range(n,n+1):
        print(i*i)
print_squares(9);
```
---

# Print squares from 1 to n

```
def print_squares(n):
    for i in range(1, n + 1):
        print(i * i)

print_squares(9)
```
---

# Print squares of first N even numbers

```
def print_even_squares(n):
    for i in range(2, 2 * n + 1, 2):
        print(f"{i}^2 = {i * i}")

print_even_squares(5)

```
