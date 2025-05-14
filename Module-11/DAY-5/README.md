# Ex.No:11(E)  JAVA HASHMAP

## AIM:
 To iterate through all elements in a TreeSet using a for loop.
## ALGORITHM :
1.Read the size n of the TreeSet.
2.Read n numbers and add them to the TreeSet (automatically sorted).
3.Use a for loop to iterate through the elements in the TreeSet.
4.Print each element during the iteration.
## PROGRAM:
 ```
/*
Program to implement a HASHMAP
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
        TreeSet<Integer>t=new TreeSet<Integer>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            t.add(sc.nextInt());
        }
        Iterator<Integer>i=t.iterator();
        while(i.hasNext()){
            System.out.println(i.next());
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a98e6813-aa44-4932-a609-2e934f175008)


## RESULT:

The program displays all elements in ascending order after reading and storing them in a TreeSet.


