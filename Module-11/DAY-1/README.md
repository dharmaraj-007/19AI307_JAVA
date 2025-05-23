# Ex.No:11(A)         JAVA TREESET
## AIM:
Write a Java program to retrieve and remove the last element of a tree set.

## ALGORITHM :
1. Start the program and create a Scanner object to take input from the user.

2. Read an integer n from the user, representing the number of elements to be added to the TreeSet.

3. Create an empty TreeSet of integers to store the input values in sorted order.

4. Use a loop that runs n times to read integers from the user and add them to the TreeSet.

5. Display the original contents of the TreeSet.

6. Retrieve and remove the last (highest) element from the TreeSet using last() and remove() methods.

7. Display the removed element and the TreeSet after deletion.

8.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
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
        TreeSet<Integer> s=new TreeSet<>();
        for(int i=0;i<n;i++){
            s.add(sc.nextInt());
        }
        System.out.println("Original tree set: "+s);
        int res=s.last();
        s.remove(res);
        System.out.println("Removes the last element: "+res);
        System.out.println("Tree set after removing last element: "+s);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/5661baf4-d4c2-4688-8880-5eed463c723c)


## RESULT:
Thus the java program to retrieve and remove the last element of a tree set was executed successfully.

