🎯 Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

🧠 Algorithm
Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
Add Code Here
```
a = 16
print(bin(a))
```


## Output
![WhatsApp Image 2025-10-14 at 20 37 54_baedc6ce](https://github.com/user-attachments/assets/d4138ab8-72fb-4d58-99cb-e6832a112bdf)



## Result
The program successfully converts the number 16 into its binary representation and displays the result as 0b10000 on the screen.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
# Define the lambda function
add = lambda a, b: a + b

# Example usage
result = add(4, 5)
print("Sum is:", result)
```
## Output
<img width="275" height="65" alt="Screenshot 2025-10-14 204349" src="https://github.com/user-attachments/assets/9e8d6bcf-939c-43d9-aeb3-f525a6c9c045" />

## Result
The program successfully created lambda function to find the sum

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
Add Code Here
```
from math import factorial

# Input number of rows
rows = int(input("Enter the number of rows: "))

# Generate Pascal's Triangle
for i in range(rows):
    # Print spaces for alignment
    print(" " * (rows - i), end="")
    
    # Calculate and print each value
    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=" ")
    print()
```


## Sample Output
<img width="637" height="139" alt="image" src="https://github.com/user-attachments/assets/977c65de-b0cc-4cb3-b434-78919ac98f58" />




## Result
The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def find_modulo(a, b):
    return a % b
result = find_modulo(17, 5)
print("17 % 5 =", result)
```

## Output
<img width="155" height="42" alt="Screenshot 2025-10-14 204951" src="https://github.com/user-attachments/assets/c4dac7cd-99d0-4917-bb77-41db2de655b6" />

## Result
The program successfully defines a function and returns the modulo of the two inputs

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
