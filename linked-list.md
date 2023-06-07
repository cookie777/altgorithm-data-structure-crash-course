
# Linked List

## Concept
- What is linked list?
- What is liked list good at?
- When is good to use liked list?
- What is head and tail in linked list?

## Analysis
What is the time complexity of folloing operations
- access by index
- insert at index
- delete at index
- joint two listed list
- add(delete) head
- add(delete) tail

## Exercise
### Exercise 01
Let's try to print all values in linked list.


```ts
class ListNode {
  val: number | null
  next: ListNode | null

  constructor(val: number | null = null, next: ListNode | null = null) {
  this.val = val
  this.next = next
  }
}

const zero = new ListNode(0)
const one = new ListNode(1)
const two = new ListNode(2)
const three = new ListNode(3)
const four = new ListNode(4)
zero.next = one
one.next = two
two.next = three
three.next = four

// Write the code to iterate and print all values connected to zero
// zero is the starting point. 
// Ideally, it should print like
// 0
// 1
// 2
// 3
// 4

```


### Exercise 02
- Let's try to implement your own list
https://leetcode.com/problems/design-linked-list/

- Hint: We can use a ListNode class used in Excersie 01
- Since 02 could be heavy task, you can try either 02 or 03

### Exercise 03
- Let's try to solve some leet code questions
- https://leetcode.com/problems/linked-list-cycle/description/
- https://leetcode.com/problems/remove-nth-node-from-end-of-list/
- https://leetcode.com/problems/reverse-linked-list/

## References
https://leetcode.com/explore/learn/card/linked-list/

# Advanced(optional): Double Liked List
- What is Doubly Linked List?
- What is pros and cons compare to Singly Linked List?
- Can you come up with good example when to use Double Liked List?😁