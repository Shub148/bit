# Clear Ith Bit in Java

## Problem Statement

Clear (set to 0) the ith bit of a number.

## Input

```text
n = 10
i = 1
```

## Output

```text
8
```

## Explanation

```text
10 = 1010

Clear 1st bit:

1010
1101
----
1000 = 8
```

## Java Code

```java
import java.util.*;
class file{
public static int clearithbit(int n , int i){
int bitmask = ~ (1<<i);
return n & bitmask;
}
public static void main(String args[]){

System.out.println(clearithbit(10 , 1));
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
