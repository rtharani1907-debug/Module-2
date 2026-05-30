# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16 
print(bin(a)
```
## Output
<img width="623" height="284" alt="Screenshot 2026-05-30 105953" src="https://github.com/user-attachments/assets/6963971d-ac61-48ad-a9c3-5fd25e50d2c4" />

## Result
Thus ,the program is executed successfully.

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
def result(a,b): 
mod=a%b 
print(f"modulo is {mod}") 
a = int(input()) 
b = int(input())
```
## Output
<img width="552" height="261" alt="Screenshot 2026-05-30 110113" src="https://github.com/user-attachments/assets/e69ed5a0-bd32-4875-9a5c-9581251f3a5f" />

## Result
Thus,the program is executed suucessfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))
```
## Output
<img width="397" height="303" alt="Screenshot 2026-05-30 110212" src="https://github.com/user-attachments/assets/afe25807-e124-4163-8858-ba2293428012" />

## Result
Thus,the program is executed successfully.

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
```
def triangle(n):
    for i in range(n):
        num=1
        row=[]
        for j in range(i+1):
            row.append(num)
            num=num*(i-j)//(j+1)
        print(*row)
n=int(input())
triangle(n)
```
## Sample Output
<img width="614" height="299" alt="Screenshot 2026-05-30 110328" src="https://github.com/user-attachments/assets/cc3c0c6a-0cc3-4991-88e8-985898c1419c" />

## Result
Thus,the program is executed successfully.

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
num=int(input()) 
rev=0 
temp=num 
while temp>0: 
rev=(10*rev)+temp%10 
temp//=10 
if rev==num: 
print("The given number {} is a Palindrome".format(num)) 
else: 
print("The given number {} is not a palindrome".format(num))
```
## Output
<img width="677" height="128" alt="Screenshot 2026-05-30 110436" src="https://github.com/user-attachments/assets/1a7f28e4-3578-4d7f-8330-36db6f37470b" />

## Result
Thus, the program was completed successfully.
