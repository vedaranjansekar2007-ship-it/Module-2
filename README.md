## EX NO 02(a)

## Aim:
Python Program to print 1 to n Odd numbers in reverse order.

## Algorithm:
Step 1: Get the input as integer. <br>
Step 2: Check the input is greater than 0. <br>
Step 3: Check the input is divided by zero and equal to 1. <br>
Step 4: print it and decrement the input. <br>

## Program:
```
n=int(input())
while n>0:
  if(n%2==1):
      print(n)
  n=n-1
```

## Output:

<img width="1170" height="470" alt="Screenshot 2025-12-28 093338" src="https://github.com/user-attachments/assets/7fe81dc3-10a6-4720-a1c0-0d7109e93373" />

## Result:
The program is executed successfully.
--------------------------------------

## EX NO 02(b)

## Aim:
Python Program to print all prime numbers within a given range.

## Algorithm:
Step 1: Get the input. <br>
Step 2: Divid the number with all possible numbers from 2 to n-1 using for loop <br>
Step 3: If the number gets divided by any of the numbers then print the number is composite <br>
Step 4: Else print the number is a prime number. <br>
Step 5: End the program. <br>

## Program:
```
a=int(input())
for i in range(2,a):
  for j in range(2,i):
      if(i%j==0):
          break
  else:
      print(i)
```

## Output:

<img width="1177" height="733" alt="Screenshot 2025-12-28 094551" src="https://github.com/user-attachments/assets/a16cdd97-d243-445b-ba22-2abe8b9e0be4" />

## Result:
The program is executed successfully.
--------------------------------------

## EX NO 02(c)

## Aim:
Python Program to find the sum of series 1!+2!+3!...+n!

## Algorithm:
Step 1: Import math. <br>
Step 2: Get the input and initialize sum = 0 <br>
Step 3: Using for loop, generate the input one-by-one. <br>
Step 4: Using math.factorial(), the sum of series is calculated. <br>
Step 5: End the program. <br> 

## Program:
```
import math
n=int(input())
s=0
for i in range(1,n+1):
    s += math.factorial(i)
print("The sum of the series = ",s)
```

## Output:

<img width="1182" height="283" alt="Screenshot 2025-12-28 095205" src="https://github.com/user-attachments/assets/3ee4baea-497b-4838-9ee1-7ce5f17cef9c" />

## Result:
The program is executed successfully.
--------------------------------------

EX NO 02(d)

## Aim:
Python Program to generate all the divisors of an integer.

## Algorithm:
Step 1: Get the input. <br>
Step 2: Generating a for loop that starts with the integer 1. <br>
Step 3: If the given input is divided by the integer from for loop, then print it. <br>
Step 4: Again moves to the next iteration. <br>
Step 5: End the program. <br>

## Program: 
```
a=int(input())
for i in range(1,a+1):
    if a%i==0:
        print(i)
```

## Output:

<img width="1173" height="465" alt="Screenshot 2025-12-28 095826" src="https://github.com/user-attachments/assets/4ba66d75-2df6-4186-aebc-5bc7df0faecc" />

## Result:
The program is executed successfully.
--------------------------------------

EX NO 02(e)

## Aim:
Write a lambda function which takes z as a parameter and returns z*2 using python.

## Algorithm:
Step 1: Get the input. <br>
Step 2: Using lambda multiply the input by 2 and assign it to a variable. <br>
Step 3: End the program. <br>

## Program:
```
a=int(input())
mul=lambda z: z*2
print(mul(a))
```

## Output:

<img width="1174" height="248" alt="Screenshot 2025-12-28 100145" src="https://github.com/user-attachments/assets/529dc7fe-ab32-40c2-b0fd-746d3f104ea0" />

## Result:
The program is executed successfully.
