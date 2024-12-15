# Basic-Programs
A simple Python program for linear search using user input.
n = int(input("Enter the limit\n"))
l = []
c = 0
print("Enter the element")
for i in range(n):
    x = int(input())
    l.append(x)
f = int(input("Enter the search element"))
for i in range(n):
    if l[i] == f:
        print("Element is found at", i)
        c = 1
        break
if c == 0:
    print("Element is not found")
