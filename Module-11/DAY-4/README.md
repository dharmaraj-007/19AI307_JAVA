# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To create a Hashtable, add objects (key-value pairs) to it, and check whether the Hashtable is empty or not using the isEmpty() method.
## ALGORITHM :
1.Create a Hashtable object.
2.Add key-value pairs (objects) to the Hashtable.
3.Use the isEmpty() method to check if the Hashtable is empty.
4.Display the result based on whether the Hashtable is empty or not.



## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
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
        Map<Integer,String>t=new Hashtable<Integer,String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            t.put(a,b);
        }
        for(Map.Entry m:t.entrySet()){
            System.out.println(m.getKey()+" "+m.getValue());
        }
        boolean isEmpty=t.isEmpty();
        System.out.println("Is HashMap is empty: " + isEmpty);
        }
    }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0536940b-87fc-4aca-8c20-8a537b1a900b)

## RESULT:
The program successfully creates a Hashtable, adds key-value pairs to it, checks if it is empty using isEmpty(), and displays the appropriate message along with the contents of the Hashtable.
