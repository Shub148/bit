# Bitwise OR Operation in Java

## Problem Statement

Given two integers, perform the Bitwise OR (`|`) operation and return the result.

## Input

* Two integer values `a` and `b`.

### Example Input

```text
a = 5
b = 3
```

## Output

```text
7
```

## Explanation

Binary representation:

```text
5 = 101
3 = 011
---------
| = 111
```

Result:

```text
7
```

## Java Code

```java
import java.util.*;
class file{
public static void main(String args[]){
System.out.println((5 | 3));
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

* Setting specific bits
* Permission management
* Feature flags
* Network programming
* Competitive programming
