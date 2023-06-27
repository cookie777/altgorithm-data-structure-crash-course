
# Stack

## Concept
- What is Stack (data structure)?
- What is difference between Stack and Queue?
- Come you can come when to use Stack?
    - Real world example is ok!


## Analysis
What is the time complexity of following operations for Stack? Why?
Since they are multiple types of queue, consider a type using **linked list**.

### Basics
- push (add an element to the Stack)
- pop (remove and return an element from the Stack)
- peek (return the element from the Stack)
- size (get the size of the Stack)
- merge two Stack

### Comparison
What if we try to implement Stack with Array instead of Linked List?
What would be the difference?


## Exercise
### Exercise 01
Let's try to implement your own Stack with using Linked-List!

```ts

class MyStack {
    constructor() {

    }

    push(value: number) {

    }

    pop(value: number): number {

    }

    peek(): number {

    }

    size(): number {

    }
}

```
```ts
class ListNode {
  val: number | null
  next: ListNode | null

  constructor(val: number | null = null, next: ListNode | null = null) {
  this.val = val
  this.next = next
  }
}
```

### Exercise 02
- Let's try to solve some leet code questions
- https://leetcode.com/problems/valid-parentheses/
- https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/
- https://leetcode.com/problems/crawler-log-folder/

