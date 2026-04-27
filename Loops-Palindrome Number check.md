## Loops in Python: Palindrome Number Checker

## Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## Program
```py

num = int(input())
temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print(f"The given number {num} is a Palindrome")
else:
    print(f"The given number {num} is not a palindrome")

```
## Output
<img width="942" height="196" alt="444885418-b257ada7-a475-4a63-b6d9-7dfc2b106ca2" src="https://github.com/user-attachments/assets/0241d1ab-ae40-4dd8-8c91-011e25b41591" />

## Result
Thus,the program is executed successfully.
