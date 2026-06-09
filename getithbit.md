# Get Ith Bit in Java

## Problem Statement

Given a number `n` and a position `i`, determine whether the ith bit is `0` or `1`.

## Input

```text
n = 10
i = 1
```

## Output

```text
1
```

## Explanation

```text
10 = 1010₂

Position: 3 2 1 0
Bits:     1 0 1 0

1st bit = 1
```

## Java Code

```java
import java.util.*;
class file {
public static int getithbit(int n , int i){
int bitmask = 1<< i;
if((n & bitmask) == 0){
return 0;
}else {
return 1;
}
}
public static void main(String[] args){
System.out.println(getithbit(10 ,2));
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
