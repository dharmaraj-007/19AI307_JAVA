# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
Create a java program to display the name with key  using map interface like key , value pair.

## ALGORITHM :

1. Start the program and create a Scanner object to read input from the user.

2. Read an integer n which represents the number of key-value pairs to be added to the map.

3. Initialize a HashMap<Integer, String> to store integer keys and string values.

4. Loop from 0 to n-1:

- In each iteration, read an integer and a string from the user.

- Insert the integer as key and string as value into the map using put() method.

5. Iterate over the map entries using a for-each loop with Map.Entry.

6. Print each key-value pair using getKey() and getValue() methods.

7. End the program.

## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        Map<Integer,String> map=new HashMap<>();
        for(int i=0;i<n;i++){
            Integer a=sc.nextInt();
            String b=sc.next();
            map.put(a,b);
        }
        for(Map.Entry en : map.entrySet()){
            System.out.println(en.getKey()+" "+en.getValue());
        }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/14ab5cfc-7d3f-4f19-b783-80b8d1e94adf)


## RESULT:
Thus the java program to display the name with key  using map interface like key , value pair was  executed and verified successfully.


