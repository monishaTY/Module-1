# Experiment No: 1e – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1.Begin the program.
2.Read the three numbers: a, b, and c from the user.
3.Compare a, b, and c to find the largest number:
    If a is greater than both b and c, then a is the maximum.
    Else, if b is greater than both a and c, then b is the maximum.
    Otherwise, c is the maximum.
4.Print the maximum value along with the input numbers in the format:
"The maximum of a, b, c is max_num."
5.Terminate the program.

## PROGRAM
```python
a = int(input())
b = int(input())
c = int(input())

print('The maximum of', end=' ')
print(a, b, c, sep=', ', end=' ')
print('is', end=' ')

print(a if (a > b and a > c) else (b if b > c else c))

```

## OUTPUT
![image](https://github.com/user-attachments/assets/26d9d8f0-b58f-421a-a23a-f5a1904808f0)

## RESULT
Thus, the Python program to find the maximum between three numbers using a conditional expression has been implemented and executed successfully.
