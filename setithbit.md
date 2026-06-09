# Set Ith Bit in Java

## Problem Statement

Set the ith bit of a number to `1`.

## Input

```text
n = 10
i = 0
```

## Output

```text
11
```

## Explanation

```text
10 = 1010
Set 0th bit

1010
0001
----
1011 = 11
```

## Java Code

```java
import java.util.*;
class file{
public static int setithbit(int n, int i){
int bitmask = 1<<i;
return n | bitmask;
}
public static void main(String args[]){
System.out.println(setithbit(10,2));
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
