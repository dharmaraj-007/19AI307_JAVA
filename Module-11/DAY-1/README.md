# Ex.No:11(A)         JAVA TREESET
## AIM:
Write a Java program to get the number of elements in a tree set

## ALGORITHM :
1.Create a TreeSet to store elements.  
2.Add some elements to the TreeSet.  
3.Use the size() method of TreeSet to get the number of elements.  
4.Display the number of elements.  
## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
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
        int size=sc.nextInt();
        TreeSet<String>t=new TreeSet<String>();
        for(int i=0;i<size;i++){
            t.add(sc.next());
        }
        System.out.println("Original tree set: " + t);
        System.out.println("Size of the tree set: " + t.size());
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0cc80da2-4c0a-4051-92e6-c13440af79e3)

## RESULT:
The program successfully gets and displays the number of elements in a TreeSet using the size() method.

