# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashtable for all input value.

## ALGORITHM :
1.Create a HashMap to store key-value pairs.
2.Add key-value pairs to the HashMap.
3.Use an iterator to iterate over the HashMap and display the key-value pairs using a while loop.
4.Display the size of the HashMap using the size() method.
5.Use the clear() method to remove all elements from the HashMap.
6.Verify that the HashMap is cleared by checking its size again.

## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
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
        HashMap<Integer,String>t=new HashMap<Integer,String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            t.put(a,b);
        }
        Iterator<Integer>i=t.keySet().iterator();
        while(i.hasNext()){
            Integer key=i.next();
            System.out.println("key: " + key + " value: " + t.get(key));
        }
            System.out.println("Size of Map: " + t.size());
            t.clear();
            System.out.println("Size of Map: " + t.size());
        }
    }
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/422d6b67396cdbbcaa0f3ed8dbd6940d310539b8/Module-11/DAY-2/9.png

## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







