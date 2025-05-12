# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1.Begin the program.
2.Read the three numbers: num1, num2, and num3 from the user.
3.Compare num1, num2, and num3 to find the smallest number:
     If num1 is less than or equal to both num2 and num3, then num1 is the minimum.
     Else, if num2 is less than or equal to both num1 and num3, then num2 is the minimum.
     Otherwise, num3 is the minimum.
4.Print the minimum value along with the input numbers in the format:
"The minimum of num1, num2, num3 is min_num."
5.Terminate the program.

## PROGRAM
```python

a=eval(input())
b=eval(input())
c=eval(input())
if a<b and a<c:
    print(f"The minimum of {a}, {b}, {c} is {a}")
elif b<c and b<a:
    print(f"The minimum of {a}, {b}, {c} is {b}")
else:
    print(f"The minimum of {a}, {b}, {c} is {c}")
    
```

## OUTPUT
![image](https://github.com/user-attachments/assets/d7a11d54-a225-4101-95d6-349e1c3b8722)


## RESULT
Thus, the Python program to find the minimum between three numbers using a conditional expression has been implemented and executed successfully.
