# Ex.No:12(A)         JAVA TREE MAP
## AIM:
To Write a Java program to get all keys from the given a Tree Map
## ALGORITHM :
1.Create a TreeMap and populate it with key-value pairs.
2.Use the keySet() method to retrieve all keys.
3.Iterate over the key set and print each key


## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        TreeMap<String,String>t=new TreeMap<String,String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            String n1=sc.next();
            String n2=sc.next();
            t.put(n1,n2);
        }
        Set<String>key=t.keySet();
        for(String a:key){
            System.out.println(a);
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/eab9d224-055f-4fbb-bec2-d80449f3c05d)

## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
