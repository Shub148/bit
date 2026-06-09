# Bitwise Right Shift (>>) in Java

## Problem Statement

Given an integer, perform the Bitwise Right Shift (`>>`) operation and return the result.

## Input

* An integer value `n`
* Number of positions to shift `k`

### Example Input

```text
n = 20
k = 2
```

## Output

```text
5
```

## Explanation

Binary representation:

```text
20 = 00010100
```

Right Shift by 2:

```text
00010100 >> 2 = 00000101
```

Decimal value:

```text
5
```

## Java Code

```java
import java.util.*;
class file{
public static void main(String args[]){
System.out.println((5>>2));
}
}
```

## Sample Output

```text
5
```

## Formula

```text
n >> k = n / 2^k
```

Example:

```text
20 >> 1 = 10
20 >> 2 = 5
20 >> 3 = 2
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

* Fast division by powers of 2
* Competitive Programming
* Binary Search Optimizations
* Operating Systems
* Low-Level Programming

## Example Table

| Number | Shift | Result |
| ------ | ----- | ------ |
| 20     | 1     | 10     |
| 20     | 2     | 5      |
| 32     | 3     | 4      |

## Conclusion

The Right Shift operator (`>>`) moves all bits to the right by a specified number of positions. Each right shift effectively divides the number by 2 while preserving the sign bit.
