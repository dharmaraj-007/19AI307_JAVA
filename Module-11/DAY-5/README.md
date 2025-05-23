# Ex.No:11(E)  JAVA HASHMAP

## AIM:
Create a java program to remove the key of 100 and to display the key and value from map .

## ALGORITHM :

1. Start the program and import necessary packages (java.util.*) for using HashMap, Scanner, and Iterator.

2. Create a HashMap<Integer, String> object to store key-value pairs where keys are integers and values are strings.

3. Read the total number of entries (n) from the user using a Scanner.

4. Use a loop to read n key-value pairs (integer and string) from the user and store them in the map using the put() method.

5. Iterate through the map keys using an Iterator, and for each key, print its corresponding value using map.get(key).

6. Remove a specific entry from the map using map.remove(key) (in this case, the key is 100) and print the removed value.

7. End the program after performing all operations.

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        HashMap<Integer,String> map=new HashMap<Integer,String>();
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
        }
        Iterator<Integer> k=map.keySet().iterator();
        while(k.hasNext()){
            Integer key =k.next();
            System.out.println("key: "+key+" value: "+map.get(key));
        }
        Integer key=100; Object value=map.remove(key); System.out.println("Following value is removed from Map: "+value);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/0d3ebb71-37b1-4e5c-8df6-d76f2f877513)


## RESULT:
Thus the java program was successfully removes the key 100 from the HashMap and displays the remaining key-value pairs.




