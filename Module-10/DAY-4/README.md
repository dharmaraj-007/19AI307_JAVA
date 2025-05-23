# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
 To create the linkedhashset , display the elements from the linkedhashset and display the size of the linkedhashset.

## ALGORITHM :
1. Start the program.

2. Create a Scanner object to take input from the user.

3. Read an integer n from the user, which indicates how many elements will be entered.

4. Create an empty LinkedHashSet<String> named cars to store unique strings while maintaining insertion order.

5. Use a loop (from 0 to n-1) to read n string inputs from the user and add each one to the cars set.

6. Print the entire contents of the LinkedHashSet.

7. Print the size of the LinkedHashSet using size() method.

8.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```

import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedHashSet<String> cars = new LinkedHashSet<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
       System.out.println("Linked HashSet :" + cars);

  

        System.out.println("Linked HashSet size:" + cars.size());
  }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/b826ddc0-88d2-4c8e-974d-ed578a22f47b)


## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.



