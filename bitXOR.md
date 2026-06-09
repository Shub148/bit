# Bitwise XOR Operation in Java

## Problem Statement

Given two integers, perform the Bitwise XOR (`^`) operation and return the result.

## Input

* Two integer values `a` and `b`.

### Example Input

```text
a = 5
b = 3
```

## Output

```text
6
```

## Explanation

Binary representation:

```text
5 = 101
3 = 011
---------
^ = 110
```

Result:

```text
6
```

## Java Code

```java
import java.util.*;
class file {
public static void main(String args[]){
System.out.println(( 5 ^ 3));
}
}
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

* Finding unique elements in arrays
* Swapping two numbers without a temporary variable
* Encryption and cryptography
* Error detection algorithms
* Competitive programming

## Special Property

```text
A ^ A = 0
A ^ 0 = A
```

Example:

```text
5 ^ 5 = 0
5 ^ 0 = 5
```
