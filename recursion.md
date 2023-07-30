
# Recursion

## Overview
- In computer science, recursion is a method of solving a computational problem where the solution depends on solutions to smaller instances of the same problem.
- Especially, we can achieve this by calling a same function in the function

```python
func factorial(n):
    if n is 0 or 1:
        return 1
    return n * Factorial(n-1)
```

## Tips

Every recursive algorithm involves at least 2 cases
1. Base(Edge) Case: A simple occurrence that can be answered directly
    - When do we **stop** the function call?
2. Recursive Case: A more complex occurrence of the problem that cannot be directly answered
    - What kind of **similar pattern** we can have?

The other ideas that may help you is as follows
- What kind of **arguments** do you pass to the function?
- What do you want to **return** for the function?
- What can kind of process do you do before and after the function call? (Back tracking)

## Drawbacks
- Recursion may cause a stack overflow since each function call will be pushed into stack
- Thus, recursion can cause more memory allocation compare to simple loop

## Exercise
- https://leetcode.com/problems/fibonacci-number/
- https://leetcode.com/problems/power-of-two/
- https://leetcode.com/problems/palindrome-number/
- https://leetcode.com/problems/reverse-linked-list/

## Exercise2 (Backtracking)
- https://leetcode.com/problems/generate-parentheses/
<!-- https://web.stanford.edu/class/archive/cs/cs106b/cs106b.1188/lectures/Lecture11/Lecture11.pdf -->