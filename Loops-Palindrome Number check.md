## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
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

## 🧾 Program
```
def tri(n):
    num=1
    for i in range(n):
        for j in range(i+1):
            print(num,end=" ")
        num+=2
        print()
n=int(input())
tri(n)
```
## Output
<img width="795" height="660" alt="image" src="https://github.com/user-attachments/assets/925cd0d9-0c2c-477c-b11f-21536760222e" />

## Result
The program is excecuted
