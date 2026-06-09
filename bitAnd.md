# Bitwise AND Operation in Java

## Problem Statement

Given two integers, perform the Bitwise AND (`&`) operation and return the result.

## Input

* Two integer values `a` and `b`.

### Example Input

```text
a = 5
b = 3
```

## Output

* An integer representing the result of the Bitwise AND operation.

### Example Output

```text
1
```

## Explanation

Binary representation:

```text
5 = 101
3 = 011
---------
& = 001
```

Result:

```text
1
```

## Java Code

```java
import java.util.*;
class file {

public static void main(String args[]){
System.out.println((5 & 3));
}
}
```

## Time Complexity

* **O(1)**

The bitwise AND operation is performed in constant time.

## Space Complexity

* **O(1)**

No extra space is used apart from a few variables.

## Applications

* Masking bits
* Checking flags
* Permission handling
* Low-level system programming
* Competitive programming
