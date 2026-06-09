# Update Ith Bit in Java

## Problem Statement

Update the ith bit of a number to a new value (0 or 1).

## Input

```text
n = 10
i = 2
newBit = 1
```

## Output

```text
14
```

## Explanation

```text
10 = 1010

Update 1st bit to 0:

1010 → 1000

Result = 8
```

## Java Code

```java
import java.util.*;
class file{
public static int setIthbit(int n, int i){
int bitmask = 1 <<i;
return n | bitmask;
}
public static int clearIthbit(int n , int i){
int bitmask = ~ (1<<i);
return n & bitmask;
}
public static int updateIthbit(int n, int i, int  newBit){
if(newBit == 0){
return clearIthbit(n, i);
} else {

return setIthbit(n , i);
}
}
public static void main(String args[]){

System.out.println(updateIthbit(10 , 2,  1));
}
}
```

## Formula

### Update to 0

```java
n = n & (~(1 << i));
```

### Update to 1

```java
n = n | (1 << i);
```

## Time Complexity

```text
O(1)
```

## Space Complexity

```text
O(1)
```
