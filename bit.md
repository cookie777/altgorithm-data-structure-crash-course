
# Bit

## Summary
 A "bit" is the smallest unit of data and information storage in computing. The term "bit" is a contraction of "binary digit." It can have one of two possible values: 0 or 1, representing the two states of a binary system, which is the foundation of digital computing

### Q0: Terms
- What is a `Byte`?
- What is `LSb` and `MSb`?

## Conversion

A machine only treats a number by binary number Where is human to understand a number by base 10.

### Q0
**Terms**

If the base is 2, 8, 10, and 16, there is a specific name for each base. The base 2 is binary. What are rest of them?

- Base 2: binary
- Base 8: ?
- Base 10: ?
- Base 16: ?

**Representation**

Sometimes you will see some symbol like `0b******` or `0x****`. What are these? Explain them with examples.


### Q1
How do you convert base 10 number to base 2 (binary) number? Write an algorithm for it. 
```ts

function convertToBase2(numBase10: number): [number] {
    // e.g, If the `num` is 11, it should return [1,0,1,1]
}

```
### Q2
How do you convert base 2 number to base 10 number? Write an algorithm for it. 

```ts

function convertToBase10(numBase2: [number]): number {
    // e.g, If the `numBase2` is [1,0,1,1], it should return 11
}

```
### Q3
How do you convert base 10 number to base 3 number? Write an algorithm for it. 

```ts

function convertToBase3(numBase10: number): [number] {
    // e.g, If the `num` is 11, it should return [1,0,2]
}
``````

### Q4
How do you convert base 10 number to base 16 number? Write an algorithm for it. 

```ts

function convertToBase16(numBase10: number): string {
    // e.g, If the `num` is 2894, it should return "B4E". 
}
``````

## Unsigned integer

🚀 For each answer, **describe the steps and processes you followed**
e.g, Answer format

```rust
Step 1. ****
Step 2. ****
Step 3. ***
Thus, the answer is ****
```

### Q1
Bits can represent an integer. An `integer` is one of the privative data type of programming language.
What is the range of 8 bits integer.?

You don't have to consider a negative number. We call this data type especially an `unsigned integer`.
An `unsigned integer` starts from zero.

### Q2
What is the range of 32 bits unsigned integer?

## Singed integer

We also want to represent a negative number by using bits.
When a integer can treat both negative and positive number, we call this type `singed integer`. There are several ways to make a negative integer. One of the common way is "Two's complement"


### Q1
Calculate the binary representation of the `8-bit signed integer -7` using the "Two's complement" method. Outline the steps and processes you followed.

### Q2
Calculate the binary representation of the `32-bit signed integer -7` using the "Two's complement" method. 
### Q3
Calculate the binary representation of the `32-bit signed integer -239,472,903` using the "Two's complement" method.

### Q4
Convert the binary value `11010101` into an `8-bit signed integer` representation using the "Two's complement" method.


## Ice Break Question

Masaki likes to play retro tv games👾. One day he was playing one of the RPG games🗡️. He finally faced the last boss 😈 and the boss's HP (hit point) was a maximum of HP 32,000. Masaki was excited but he'd wrongly casted a spell of healing the HP (increasing the HP) ❤️‍🩹 to the Boss instead of a fire attack🧙‍♂️. The boss got healed by + HP 1,000. 

However, as soon as the boss got healed, it got died and defeated😇. Can you assume and explain what happened? 😁


One of the Answers: [Integer overflow](https://en.wikipedia.org/wiki/Integer_overflow) 

# Bitwise operation

Bitwise operations are fundamental operations performed on individual bits (binary digits) within a binary representation of data. 

## Basics
### Exercise01
There are mainly six common bitwise operations. List up all of them with example.

- 
-
-
-
-
-

### Exercise02
and what are time complexity of all bitwise operations?

### Exercise03
What are the benefits of using bit operations?

## Tips and tricks
### Exercise01
How do you write a code that determines that if the input number is odd or even?
Can you write a code without using any math operators `+, -, *, /`? 😁


**Constraints:**
- input: 32 bit signed integer

```ts
function isOdd(input: number): bool {

}
```

### Exercise02
Can you write a code which multiplies the input number by 2 and 4 without using `*`? 😁

**Constraints:**
- input: 32 bit unsigned integer
- You don't have to care about integer overflow

```ts
function multiplyByTwo(input: number): number {

}
```

```ts
function multiplyByFour(input: number): number {

}
```

### Exercise03
Can you write a code which divides the input number by 2 or 4 without using `/`? 😁

**Constraints:**
- input: 32 bit unsigned integer
- The result will be always round down
- You don't have to care about integer overflow

```ts
function divideByTwo(input: number): number {

}
```
```ts
function divideByFour(input: number): number {

}
```

### Exercise04
Write a code which inverts the sign of number. 

e.g, `invertSign(3) -> -3`, `invertSign(-6) -> 6`

Can you write the code without using `-` nor `*`? 😁

**Constraints:**
- input: 32 bit signed integer


```ts
function invertSign(input: number): number {

}

```


## LeadCode Practice
**Do not use a build in library such as count bits**

- https://leetcode.com/problems/number-of-1-bits/
- https://leetcode.com/problems/hamming-distance/submissions/
- https://leetcode.com/problems/single-number/
- https://leetcode.com/problems/power-of-two/

## Ice Break Question 02

🚧


## Tips and tricks: Advanced (Optional)
### Exercise05: Set a Bit 
Write a code which set the specific `n` th digit to `1`. 
e.g,
``` 
- input: 0 (Ob00000000), digit: 2 -> return: 4 (0b00000100)
- input: 89 (Ob01011001), digit: 5 -> return: 121 (Ob01111001)
```

**Constraints:**
- input: 32 bit signed integer
- 0 < digit < 32 


```ts
function setBit(input: number, digit: number): number {

}

```

### Exercise06: Clear a Bit 
Write a code which clear the specific `n` th digit to `1`. 
e.g,
``` 
- input: -1 (Ob11111111), digit: 3 -> return: 9 (Ob11110111)
- input: 89 (Ob01011001), digit: 6 -> return: 25 (Ob00011001)
```

**Constraints:**
- input: 32 bit signed integer
- 0 < digit < 32 

```ts
function clearBit(input: number, digit: number): number {

}

```


bit flag
game reduce


https://leetcode.com/tag/bit-manipulation/discuss/2960396/Bit-Manipulation-Guide-and-Tricks