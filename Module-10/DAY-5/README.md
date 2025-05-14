# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
To demonstrate the use of LinkedList in Java by reading the size of the list, adding elements, and displaying them while applying collection concepts.
## ALGORITHM :
1.Create a LinkedList to store the elements.
2.Read the size of the list from the user.
3.Read the elements from the user and add them to the LinkedList.
4.Display the elements of the LinkedList using a loop.
5.Apply collection concepts like iterating over the list.

## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
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
        LinkedList<String>al=new LinkedList<String>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            al.add(sc.next());
        }
        System.out.println(al);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/434df3c1-ae0e-46c6-84a3-b85f7e76a4f3)

## RESULT:
The program reads the size and elements for a LinkedList from the user, displays the elements, and demonstrates the use of collection concepts in Java.
