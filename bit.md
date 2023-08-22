
# Bit

## Summary
 A "bit" is the smallest unit of data and information storage in computing. The term "bit" is a contraction of "binary digit." It can have one of two possible values: 0 or 1, representing the two states of a binary system, which is the foundation of digital computing

### Q0
Then, what is a `Byte`?

## Conversion

A machine only treats a number by binary number Where is human to understand a number by base 10.

### Q0: Terms

If the base is 2, 8, 10, and 16, there is a specific name for each base. The base 2 is binary. What are rest of them?

- Base 2: binary
- Base 8: ?
- Base 10: ?
- Base 16: ?



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


## Unsigned integer

🚀 For each answer, **describe the steps and processes you followed**
e.g, Answer format

```
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


<!-- [Integer overflow](https://en.wikipedia.org/wiki/Integer_overflow) -->
