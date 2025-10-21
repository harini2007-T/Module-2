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
Add code Here
```
# Palindrome Number Checker

# Step 1: Get input from user
num = int(input("Enter a number: "))

# Step 2: Store original number in temp
temp = num

# Step 3: Initialize rev to 0
rev = 0

# Step 4: Reverse the number using while loop
while temp > 0:
    rev = (rev * 10) + (temp % 10)
    temp = temp // 10

# Step 5: Check if palindrome
if num == rev:
    print(f"{num} is a palindrome number.")
else:
    print(f"{num} is not a palindrome number.")
```
## Output
<img width="797" height="67" alt="image" src="https://github.com/user-attachments/assets/bdf503b2-c6f1-4494-9501-9405560fb05e" />

## Result
The program successfully takes a number as input from the user, reverses it using a while loop, and compares it with the original number.
If both are equal, it confirms that the number is a palindrome; otherwise, it displays that it is not a palindrome.
\
