# 🔁 `for` Loop in Python


## ✅ Basic Syntax

```python
for variable in iterable:
    # block of code
```
- `iterable` can be a list, tuple, string, range, or any object that yields items one by one.
- `variable` takes each value in sequence.

---

## 🔹 1. Looping Over a Range (Java Equivalent: `for (int i = 0; i < n; i++)`)

```python
for i in range(5):
    print(i)
```
**Output:**
```
0
1
2
3
4
```
> Note: `range(5)` produces 0 to 4 (not including 5).

---

## 🔹 2. `range(start, end, step)`

```python
for i in range(1, 10, 2):
    print(i)
```
**Output:**
```
1
3
5
7
9
```

---

## 🔹 3. Looping Over a List

```python
fruits = ["apple", "banana", "mango"]
for fruit in fruits:
    print(fruit)
```

---

## 🔹 4. Looping Over a String

```python
for char in "Python":
    print(char)
```

---

## 🔹 5. Loop with `else` (Unique to Python)

```python
for i in range(3):
    print(i)
else:
    print("Loop finished")
```
> The `else` block runs if the loop completes normally (no `break`).

---

## 🔹 6. Using `break` and `continue`

```python
for i in range(1, 10):
    if i == 5:
        break
    print(i)
```
```python
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
```

---

## 🔹 7. Nested `for` Loops

```python
for i in range(3):
    for j in range(2):
        print(f"i={i}, j={j}")
```

---

## 🔹 8. Using `enumerate()` (Index + Value)

```python
colors = ['red', 'blue', 'green']
for index, color in enumerate(colors):
    print(index, color)
```

---

## 🔹 9. Using `zip()` (Parallel Looping)

```python
names = ['Alice', 'Bob', 'Charlie']
scores = [90, 85, 88]
for name, score in zip(names, scores):
    print(f"{name} scored {score}")
```

---

## 🔹 10. List Comprehension (Pythonic Shortcut)

```python
squares = [i * i for i in range(1, 6)]
print(squares)
```

---

