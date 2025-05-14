# Ex.No:10(A)  JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
 To create an ArrayList of car names, add a new car at the 3rd position, and then display the list in alphabetical order.
## ALGORITHM:
1.Create an ArrayList of String to store car names.
2.Add four car names to the list.
3.Insert a new car name at the 3rd position (index 2).
4.Sort the list in alphabetical order.
5.Display the sorted list.

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        ArrayList<String> cars=new ArrayList<String>();
        Scanner sc=new Scanner(System.in);
        for(int i=0;i<4;i++)
        {
            cars.add(sc.next());
        }
        cars.add(3,sc.next());
        Collections.sort(cars);
        for(String i : cars){
            System.out.println(i);
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a09dc50a-c745-4694-9365-99242fdb9052)

## RESULT:
The program successfully adds car names to an ArrayList, inserts a new car at the 3rd position, sorts the list alphabetically, and displays the result.

