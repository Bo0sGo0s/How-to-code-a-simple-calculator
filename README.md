# How-to-code-a-simple-calculator
How to code a simple calculator!
In this short github tutorial i will show you how to quickly code a simple calculator

First of all we will be starting with the main code 

main.py

This is basically the essentials in an elongated term.
```python
a=0
b=1
c=2
d=3
e=4
f=5
g=6
h=7
i=8
j=9

choice = float(input("Enter a number: "))
print(choice)
num = choice
if num == a:
    if num == a:
        print("Zero")
elif num == b:
    print("One")
elif num == c:
    print("Two")
elif num == d:
    print("Three")
elif num == e:
    print("Four")
elif num == f:
    print("Five")
elif num == g:
    print("Six")
elif num == h:
    print("Seven")
elif num == i:
    print("Eight")
elif num == j:
    print("Nine")

choice1 = float(input("Enter a number: "))
print(choice1)
num1 = choice1
if num1 == a:
    if num1 == a:
        print("Zero")
elif num1 == b:
    print("One")
elif num1 == c:
    print("Two")
elif num1 == d:
    print("Three")
elif num1 == e:
    print("Four")
elif num1 == f:
    print("Five")
elif num1 == g:
    print("Six")
elif num1 == h:
    print("Seven")
elif num1 == i:
    print("Eight")
elif num1 == j:
    print("Nine")

s = float(input("Enter a number: "))
print(s)
if s == b:
	if s == b:
		res = num+num1
		print("\nAddition Result = ", res)
elif s == c:
	res = num-num1
	print("Subtraction Result = ", res)
elif s == d:
	res = num*num1
	print("Multiplication Result = ", res)
elif s == e:
	res = num/num1
	print("Division Result = ", res)
```

First we start by enumerating the variables
```python
a=0
b=1
c=2
d=3
e=4
f=5
g=6
h=7
i=8
j=9
```
then by insterting 
```python
choice = float(input("Enter a number: "))
```
we are telling it that we want to insert a number

then with the lines 
```python
print(choice)
num = choice
```
We are stating that we print the chosen number and the choice will equal num wich i will explain later.

now using if... else... elif... we are basicaly just telling the engine that x (x being a,b,c,d,e,f,g... ect) x = the number that its associated with letters.

```python
if num == a:
    if num == a:
        print("Zero")
elif num == b:
    print("One")
elif num == c:
    print("Two")
elif num == d:
    print("Three")
elif num == e:
    print("Four")
elif num == f:
    print("Five")
elif num == g:
    print("Six")
elif num == h:
    print("Seven")
elif num == i:
    print("Eight")
elif num == j:
    print("Nine")
```
Here we are doing the same thing again

```python
choice1 = float(input("Enter a number: "))
print(choice1)
num1 = choice1
if num1 == a:
    if num1 == a:
        print("Zero")
elif num1 == b:
    print("One")
elif num1 == c:
    print("Two")
elif num1 == d:
    print("Three")
elif num1 == e:
    print("Four")
elif num1 == f:
    print("Five")
elif num1 == g:
    print("Six")
elif num1 == h:
    print("Seven")
elif num1 == i:
    print("Eight")
elif num1 == j:
    print("Nine")
```

Now this is telling it what formula to use: 1 = addition, 2 = Substraction, 3 = Multiplication, 4 = Division

```python
s = float(input("Enter a number: "))
print(s)
if s == b:
	if s == b:
		res = num+num1
		print("\nAddition Result = ", res)
elif s == c:
	res = num-num1
	print("Subtraction Result = ", res)
elif s == d:
	res = num*num1
	print("Multiplication Result = ", res)
elif s == e:
	res = num/num1
	print("Division Result = ", res)
```
