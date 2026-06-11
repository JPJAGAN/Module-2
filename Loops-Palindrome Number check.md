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

<img width="1032" height="278" alt="{0AE7CE82-9138-4D7B-8FDF-BC946B4E7793}" src="https://github.com/user-attachments/assets/6e4fa9ff-0b24-43b2-b976-11f36d6f7718"/>

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
