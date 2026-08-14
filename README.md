# 💻 Daily Programming Challenge

Consistent daily Python practice — solving problems, tracking progress, and building interview-ready problem-solving skills for placements.

## 🎯 Goal

Solve at least one problem every day

### 1.Print "Hello World"
```Python
print("Hello World")
```

### 2.Print your name, age, and college
```Python
name="sabarinathan"
age=20
college="jct"
print(name)
print(age)
print(college)
```

### 3. Sum of Two Numbers
```Python
a=int(input())
b=int(input())
print(a+b)
```

### 4.Subtract two numbers
```Python
a=int(input())
b=int(input())
print(a-b)
```

### 5.Multiply two numbers
```Python
a=int(input())
b=int(input())
print(a*b)
```

### 6.Divide two numbers
```Pyhton
a=int(input())
b=int(input())
print(a/b)
```

### 7. Find remainder
```Python
a=int(input())
b=int(input())
print(a%b)
```

### 8. Find quotient
```Python
a=int(input())
b=int(input())
print(a//b)
```

### 9.Swap two numbers (using third variable)
```Python
a=int(input())
b=int(input())
temp=a
a=b
b=temp
print(a,b)
```

### 10.Swap two numbers (without third variable)
```Python
a=int(input())
b=int(input())
a,b=b,a
print(a,b)
```
## 2.inputs & outputs
### 11. Read an integer and print it.
```Python
a=int(input())
print(a)
```

### 12. Read a float and print it.
```Python
a=float(input())
print(a)
```

### 13. Read a string and print it.
```Python
a=str(input())
print(a)
```

### 14.Read three numbers and find their sum
```Python
a=int(input())
b=int(input())
c=int(input())
total=a+b+c
print(total)
```

### 15. Calculate simple interest
```Python
p=float(input())
r=float(input())
t=float(input())
si=(p*r*t)/100
print(si)
```

### 16.Calculate compound interest
```Python
p=float(input())
r=float(input())
t=float(input())
a=p*(1+r/100)**t
ci=a-p
print(ci)
```

### 17.Calculate area of circle
```Python
import math
r=float(input())
area=math.pi*r*r
print(area)
```

### 18.Calculate area of rectangle
```Python
l=float(input())
b=float(input())
area=l*b
print(area)
```

### 19.Calculate area of triangle
```Python
base=float(input())
height=float(input())
area=0.5*base*height
print(area)
```

### 20.Convert Celsius to Fahrenheit 
```Python
celsius=float(input())
fahrenheit=(9/5)*celsius+32
print(fahrenheit)
```   
## 3. Operators
### 21.Check even or odd
```Python
a=int(input())
if a%2==0:
   print("even")
else:
   print("odd")
```
### 22.Greatest of two numbers
```Python
a = int(input())
b = int(input())

if a > b:
    print(a)
else:
    print(b)
```

### 23.Greatest of three numbers
```Python
a = int(input())
b = int(input())
c = int(input())

if a >= b and a >= c:
    print(a)
elif b >= a and b >= c:
    print(b)
else:
    print(c)
```
### 24.Positive, negative, or zero
```Python
n = int(input())

if n > 0:
    print("Positive")
elif n < 0:
    print("Negative")
else:
    print("Zero")
```    
### 25.Find smallest of three numbers
```Python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a <= b and a <= c:
    print("Smallest number is:", a)
elif b <= a and b <= c:
    print("Smallest number is:", b)
else:
    print("Smallest number is:", c)
```

### 26.Check divisible by 5 and 11
```Python
num = int(input("Enter a number: "))

if num % 5 == 0 and num % 11 == 0:
    print("The number is divisible by both 5 and 11")
else:
    print("The number is not divisible by both 5 and 11")
```

### 27.Check multiple of 7
num = int(input("Enter a number: "))

if num % 7 == 0:
    print("It is a multiple of 7")
else:
    print("It is not a multiple of 7")
    ```
