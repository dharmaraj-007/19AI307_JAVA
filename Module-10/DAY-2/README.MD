# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To create a LinkedList, read three elements from the user, display the elements, and apply the clone() method to create a copy of the LinkedList.

## ALGORITHM :
1.Create a LinkedList to store the elements.
2.Read three elements from the user and add them to the list.
3.Display the elements of the original LinkedList.
4.Clone the original LinkedList using the clone() method.
5.Display the cloned list.





## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
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
        LinkedList<String>lis=new LinkedList<String>();
        for(int i=0;i<3;i++){
            lis.add(sc.next());
        }
        System.out.println("Linked List 1:" + lis);
        LinkedList lis1=new LinkedList();
        lis1=(LinkedList)lis.clone();
        System.out.println("Linked List 2:" + lis1);
    }
}
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/de8ef7bdc331c34d588c30da6ce129ada26471f0/Module-10/DAY-2/8.png

## RESULT:
The program successfully creates a LinkedList, reads three elements, displays the original list, clones the list using the clone() method, and displays the cloned list.





