# base-practice-project

## Day 1
Started Python practice

## Day 2
- Learned Python basics
- Created the first script

# commit 1
print("hello")

# commit 2
print("ritik")

## commit 3
print("hello base")

## commit 4
print("this time now to lonch")

## commit 5
print("base last 1 year to I join") 

## commit 6
# Variables example
a = 10
b = 20
print(a + b) 

## commit 7
# User input
name = input("Enter name: Ritik")
print("Hello", name)

## commit 8
# If-else condition
num = 5
if num > 0:
    print("Positive")

## commit 9
# Loop example
for i in range(5):
    print(i)

## commit 10
# While loop
i = 1
while i <= 5:
    print(i)
    i += 1

## commit 11
# Function example
def greet():
    print("Welcome")
greet() 

## commit 12
# Sum function
def add(a, b):
    return a + b
print(add(3, 4))

## commit 13
# List example
nums = [1,2,3]
print(nums)

## commit 14
# List loop
for n in [1,2,3]:
    print(n) 

## commit 15
# String reverse
text = "python"
print(text[::-1])

## commit 16
# Even odd
n = 4
print("Even" if n%2==0 else "Odd")

## commit 17
# Factorial
fact = 1
for i in range(1,6):
    fact *= i
print(fact)

## commit 18
# Fibonacci
a,b = 0,1
for _ in range(5):
    print(a)
    a,b = b,a+b

## commit 19
# Dictionary
d = {"a":1,"b":2}
print(d)

## commit 20
# Set example
s = {1,2,3}
print(s)

## commit 21
# Tuple
t = (1,2,3)
print(t)

## commit 22
# Max number
print(max([1,5,3]))

## commit 23
# Min number
print(min([1,5,3]))

## commit 24
# Length
print(len("python"))

## commit 25
# Type check
print(type(10))

## commit 26
# Simple calculator
a,b=5,2
print(a+b,a-b,a*b,a/b)

## commit 27
# Square numbers
for i in range(5):
    print(i*i)

## commit 28
# Palindrome
s="madam"
print(s==s[::-1])

## commit 29
# Prime check
n=7
for i in range(2,n):
    if n%i==0:
        print("Not Prime")
        break
else:
    print("Prime")

## commit 30
# Count vowels
text="hello"
print(sum(1 for c in text if c in "aeiou"))

## commit 31
# Swap numbers
a,b=1,2
a,b=b,a
print(a,b)

## commit 32
# Remove duplicates
lst=[1,1,2,3]
print(set(lst))

## commit 33
# Sort list
lst=[3,1,2]
lst.sort()
print(lst)

## commit 34
# Lambda function
square = lambda x: x*x
print(square(5))

## commit 35
# End of challenge
print("50 commits completed")
