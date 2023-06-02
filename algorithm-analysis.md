# Algorithm Analysis

---

## Basics

- What is time complexity?
- What is space complexity?
- Why and when do we use time (space) complexity?
- Is running time == time complexity?
- Is number of calculations == time complexity?

## What are the complexity of these functions?

```python

def q0(n):
		print(n)
			
def q1(n):
    i = 0
    while i < n:
        print(i)
        i += 1
        
def q2(n):
    i = 0
    while i < n:
        print(i)
        i += 2

def q3(n):
    i = 1
    while i < n:
        print(i)
        i *= 2
        
def q4(n):
    i = 0
    while i < n:
        j = 0
        while j < n:
            print(i, j)
            j += 1
        i += 1
        
def q5(n):
    i = 0
    while i < n:
        j = 0
        while j < n:
            k = 0
            while k < n:
                print(i, j, k)
                k += 1    
            j += 1
        i += 1

def q6(n):
    i = 0
    while i < n:
        j = 0
        while j < i:
            print(i, j) 
            j += 1
        i += 1

def q7(n):
    i = 0
    while i < 100000000:
        print(i)
        i += 1

def q8(n):
    i = 0
    while i < n:
        j = 0
        while j < 100000000:
            print(i, j)
            j += 1
        i += 1
	
def q9(n):
    i = 0
    while i < n:
        print(i)
        i += 1

    i = 0
    while i < n:
        j = 0
        while j < n:
            print(i, j)
            j += 1
        i += 1

def q10(n):
    i = 0
    while i < n:
        print(i)
        i += 1

    i = 0
    while i < n:
        j = 0
        while j < n:
            print(i, j)
            j += 1
        i += 1
	
    i = 0
    while i < n:
        j = 0
        while j < 100000000:
            print(i, j)
            j += 1
        i += 1
	
    i = 1
    while i < n:
        print(i)
        i *= 2

```

## Optional: Try to Implement a 
- function which time complexity is O(n!)
- function which time complexity is O(log n)
