
# Queue

## Concept
- What is Queue  (data structure)?
- What is difference between Queue and Array. Pros and Cons
- Come you can come when to use  Queue?
    - Real world example is ok!


## Analysis
What is the time complexity of following operations for Queue? Why?
Since they are multiple types of queue, consider a type using **linked list**.

### Basics
- enqueue (add an element to the Queue)
- dequeue (remove and return an element from the Queue)
- peek (return an element from the Queue)
- size (get the size of the Queue)
- merge two Queue

### Comparison
What if we try to implement Queue with Array instead of Linked List?
What would be the difference?


## Exercise
### Exercise 01
Let's try to implement your own Queue with using Linked-List!

```ts

class MyQueue {
    constructor() {

    }

    enqueue(value: number) {

    }

    dequeue(value: number): number {

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
- https://leetcode.com/problems/number-of-recent-calls/
<!-- - https://leetcode.com/problems/reveal-cards-in-increasing-order/ ?? -->

