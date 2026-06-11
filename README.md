## Built-in Functions -Binary Conversion Using Built-in Functions in Python
## Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## Algorithm
1.Assign the value 16 to a variable a.
2.Use the built-in bin() function to convert the number to binary.
3.Print the result.

## Program
```
x=16
y=bin(x)
print(y)
```
## Output

<img width="395" height="330" alt="{BE2A80D4-BFB2-4F6E-AE33-FD6478021F6D}" src="https://github.com/user-attachments/assets/a60e69e1-51f8-4912-8ddb-c8fbcfd0a7a4" />

## Result

Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

## Functions in Python: Modulo Calculator
## Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## Algorithm

1.Define a function called result that takes two arguments a and b.
2.Inside the function, compute the modulo using a % b.
3.Print the result of the modulo operation.
4.Get two integer inputs from the user.
5.Call the result function with the user-provided values.
## Program
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```
## Output:

<img width="692" height="337" alt="{A6974950-6A0A-446E-B207-E8BA0772BCED}" src="https://github.com/user-attachments/assets/5f86578b-2fa9-46d9-8d81-3200e29cb4f0" />

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.

## Lambda Function in Python: Addition of Two Numbers
## Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## Algorithm
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.
## Program

```
i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))
```
## Output

<img width="538" height="409" alt="{5A575DA1-485D-49D2-9D76-4F63310A07B4}" src="https://github.com/user-attachments/assets/5cbd6452-833b-4dd9-971b-0b48c8d1023f" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

## Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## Algorithm

Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
## Program
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```
## Output

<img width="656" height="738" alt="{4B6E7EAC-3F5A-40F8-9C27-9A8BE6496148}" src="https://github.com/user-attachments/assets/2171b217-56fc-4ccd-ae53-d442a810460d" />

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

## Loops in Python: Palindrome Number Checker
## Aim
To write a Python program that checks whether a given number is a palindrome using loops.

## Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
## Program
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

<img width="1032" height="278" alt="{0AE7CE82-9138-4D7B-8FDF-BC946B4E7793}" src="https://github.com/user-attachments/assets/6e4fa9ff-0b24-43b2-b976-11f36d6f7718" />

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
