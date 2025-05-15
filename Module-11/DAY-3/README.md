# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :
To retrieve a value from a LinkedHashMap using a specific key (in this case, the key is 100).

## ALGORITHM :
1.Create a LinkedHashMap and add key-value pairs to it.   
2.Use the get() method to retrieve the value associated with the key 100.  
3.Display the retrieved value.  

## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
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
        LinkedHashMap<Integer,String>t=new LinkedHashMap<Integer,String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            t.put(a,b);
        }
        for(Map.Entry m:t.entrySet()){
            System.out.println(m.getKey()+" "+m.getValue());
        }
        Integer key=100;
        String value=t.get(key);
        System.out.println("value: "+ value);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/ccd0ff84-67e5-4cf0-9611-adc81321426e)

## RESULT:
The program successfully retrieves the value "Charlie" from the LinkedHashMap using the key 100 and displays it.





