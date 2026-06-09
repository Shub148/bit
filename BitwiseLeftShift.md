# Bitwise Left Shift (<<) in Java

## Problem Statement

Given an integer, perform the Bitwise Left Shift (`<<`) operation and return the result.

## Input

* An integer value `n`
* Number of positions to shift `k`

### Example Input

```text
n = 5
k = 1
```

## Output

```text
10
```

## Explanation

Binary representation:

```text
5 = 00000101
```

Left Shift by 1:

```text
00000101 << 1 = 00001010
```

Decimal value:

```text
10
```

## Java Code

```java
import java.util.*;
class file {
public static void main(String args[]){
System.out.println((5<<2));
}
}
```

## Sample Output

```text
10
```

## Formula

```text
n << k = n × 2^k
```

Example:

```text
5 << 1 = 10
5 << 2 = 20
5 << 3 = 40
```

## Time Complexity

```text
O(1)
```

## Space Complexity

```text
O(1)
```

## Applications

* Fast multiplication by powers of 2
* Competitive Programming
* Bit Manipulation Problems
* Computer Architecture
* Embedded Systems

## Example Table

| Number | Shift | Result |
| ------ | ----- | ------ |
| 5      | 1     | 10     |
| 5      | 2     | 20     |
| 8      | 1     | 16     |

## Conclusion

The Left Shift operator (`<<`) moves all bits to the left by a specified number of positions. Each left shift effectively multiplies the number by 2.
