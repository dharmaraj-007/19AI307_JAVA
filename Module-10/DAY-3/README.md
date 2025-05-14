# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :
To store a group of employee names in a HashSet, and retrieve the elements one by one using an Iterator.

## ALGORITHM :
1.Create a HashSet to store employee names.
2.Add employee names to the HashSet.
3.Create an Iterator to traverse the HashSet.
4.Use the Iterator to retrieve and display each element.



## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: Bala R
RegisterNumber:  212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        HashSet<String>al=new HashSet<String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            al.add(sc.next());
        }
        Iterator<String>i=al.iterator();
        while(i.hasNext()){
            System.out.println(i.next());
        }
        
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c6e5dfbb-872e-45ee-9bd6-31273283e072)

## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










