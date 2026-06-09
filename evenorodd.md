``` JAVA - CODE

import java.util.Scanner;
class file {
    public static void evenorodd(int a, int b){
        int result =  a + b;
        if(result % 2 == 0){
            System.out.println("Even");
        } else{
            System.out.println("Odd");
        }
    }
    
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int a =  sc.nextInt();
        int b =  sc.nextInt();
    evenorodd(a , b);
    }
}

```
