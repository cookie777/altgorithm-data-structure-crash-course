
# Array

## Q: Concept
- what is array?
- how do we allecate memery when constructing the array?
- what is fixed size vs dynamic size array?
- what is pros and cons about array?
    - when do we use array? 

## Q: What is the time & space complexity of following instruction. Why do think that?

- insert (push)
- delete by index
- access by index
- find a specific value
- pop (delete last)
- pop left (delte first, shift)


## Excursive

Let's try to implement an dynamic size array with using only fixed size array.
Since there is no fixed size array in Ts, sudo code is ok

```ts
class DynamicArray {
    this.array: FixedArray<number> // Suppose this is ts Array with Fixed size. You can use every ts Array features but the fixed size. 

    public constructor(size: number) {
        this.array = new FixedArray(size)
        // Feel free to add any class properties if needed
    };

    func isEmpty(): bool {

    }

    func getLength(): number {

    }

    func push(value: number) {

    }

    func push(array: FixedArray<number>) {

    }

    func removeAt(index: number) {

    }
}
```

## Remove Master

### Task1:
Congratulation! You'are hired by that Big tech company😎
Your first job is to implement 
- `removeAt` function which removes an element at the givien index
- `removeAll` function which removes all the elements that matches to the given element.

```ts
func removeAt(arr: Array<number>, index: number) {
    // implement your code
    // e.g.  removeAll([1,4,5,6], 2) -> [1,4,6]
}

func removeAll(arr: Array<number>, value: number) {
    // implement your code
    // e.g.  removeAll([1,4,5,6,3,4,2,4], 4) -> [1,5,6,3,2]
}

```

### Task2:
Easy Peasy? What is your codes **time complexity and space complexity.**

### Task3: optional
Since your company is big and needs to handle a large amount of data,
you are asked to make it as efficient as possible.

Can you make it O(n) time complexity and O(1) space complexity for both functions? 😁
Let's try and get the bonus!