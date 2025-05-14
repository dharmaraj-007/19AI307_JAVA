# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
To demonstrate the use of HashSet in Java by adding elements to the HashSet and then displaying the elements.

## ALGORITHM :
1.Create a HashSet to store unique elements.
2.Add various elements (such as strings or numbers) to the HashSet.
3.Display the elements of the HashSet. Since HashSet does not maintain any specific order, the output may vary in the order of insertion.

## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        HashSet<String>hs=new HashSet<String>();
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            hs.add(sc.next());
        }
        System.out.println("Values in HashSet object: "+ hs);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/29a709a1-240c-4e7b-ac73-5c89fd77b0c8)

## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.



