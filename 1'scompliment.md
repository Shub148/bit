# 1's Complement in Java

## Problem Statement

Given a binary number, find its **1's Complement** by flipping all bits. Every `0` becomes `1`, and every `1` becomes `0`.

## Input

* A binary number or an integer value.

### Example Input

```text
5
```

## Output

```text
2
```

## Explanation

Binary representation of 5:

```text
5 = 0101
```

1's Complement:

```text
1010
```

Decimal value:

```text
10
```

For a 4-bit representation:

```text
0101 → 1010
```

## Java Code

```java
import java.util.*;
class file{
public static void main(String args[]){
System.out.println((~5));
}
}
```

## Sample Output

```text
1's Complement: -6
```

### Why Negative?

Java uses **2's Complement** representation for signed integers.

```text
~5 = -6
```

because:

```text
00000101 (5) - Starting me zero so it is most significant beat (MSB), so it is positive
11111010 (-6) - Starting me negative so it is least significant beat (MSB), so it is negative

## Time Complexity

```text
O(1)
```

Using the `~` operator.

For binary string conversion:

```text
O(n)
```

where `n` is the number of bits.

## Space Complexity

```text
O(1)
```

Using the `~` operator.

For binary string conversion:

```text
O(n)
```

## Applications

* Digital Electronics
* Computer Architecture
* Error Detection Systems
* Binary Arithmetic
* Competitive Programming
* Low-Level Programming

## Key Formula

```text
1's Complement = ~N
```

## Example Table

| Number | Binary | 1's Complement |
| ------ | ------ | -------------- |
| 5      | 0101   | 1010           |
| 7      | 0111   | 1000           |
| 10     | 1010   | 0101           |

## Conclusion

1's Complement is obtained by inverting all bits of a binary number. In Java, it is performed using the bitwise NOT (`~`) operator and is commonly used in low-level programming, computer architecture, and bit manipulation problems.
