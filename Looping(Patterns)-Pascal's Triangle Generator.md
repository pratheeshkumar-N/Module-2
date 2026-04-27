# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```py

n = int(input())
for i in range(n):
    print(" " * (n - i - 1), end="")  
    val = 1
    for j in range(i + 1):
        print(val, end=" ")
        val = val * (i - j) // (j + 1)
    print()
```
## Sample Output

<img width="610" height="685" alt="444884854-0d259eb8-9576-497a-a5bf-679421b37a7a" src="https://github.com/user-attachments/assets/81d2a2c0-99aa-4e72-be30-32ddca65af8a" />

## Result
Thus,the program is executed successfully.
