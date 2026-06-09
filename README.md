# Bit Manipulation

## Introduction

Bit Manipulation is a technique used to perform operations directly on the binary representation of numbers. It is widely used in competitive programming, system programming, cryptography, and technical interviews because bitwise operations are extremely fast and memory-efficient.

## Common Bitwise Operators

| Operator    | Symbol | Description                            |
| ----------- | ------ | -------------------------------------- |
| AND         | `&`    | Sets bit to 1 if both bits are 1       |
| OR          | `\|`   | Sets bit to 1 if at least one bit is 1 |
| XOR         | `^`    | Sets bit to 1 if bits are different    |
| NOT         | `~`    | Inverts all bits                       |
| Left Shift  | `<<`   | Shifts bits to the left                |
| Right Shift | `>>`   | Shifts bits to the right               |

## Example

```java
int a = 5;   // 101
int b = 3;   // 011

System.out.println(a & b); // 1
System.out.println(a | b); // 7
System.out.println(a ^ b); // 6
```

## Important Bit Manipulation Techniques

### 1. Check if a Number is Even or Odd

```java
if ((n & 1) == 0)
    System.out.println("Even");
else
    System.out.println("Odd");
```

### 2. Check if a Number is a Power of Two

```java
boolean isPowerOfTwo = (n > 0) && ((n & (n - 1)) == 0);
```

### 3. Count Set Bits

```java
int count = Integer.bitCount(n);
```

### 4. Find the Unique Element

```java
int result = 0;
for (int num : arr) {
    result ^= num;
}
```

### 5. Swap Two Numbers Without a Temporary Variable

```java
a = a ^ b;
b = a ^ b;
a = a ^ b;
```

## Advantages

* Faster execution than arithmetic operations.
* Optimizes memory usage.
* Useful in algorithm design and competitive programming.
* Frequently asked in coding interviews.

## Time Complexity

Most bitwise operations execute in:

```text
O(1)
```

## Space Complexity

```text
O(1)
```

## Applications

* Competitive Programming
* Data Compression
* Cryptography
* Network Programming
* Operating Systems
* Embedded Systems
* Game Development

## Conclusion

Bit Manipulation is a powerful technique that allows developers to solve problems efficiently by operating directly on binary data. Mastering bitwise operations improves problem-solving skills and is valuable for coding interviews at companies such as Amazon, Google, Microsoft, and Meta.
