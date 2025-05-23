# Ex.No:10(B) JAVA LINKED LIST
## AIM :
Apply the Collection Concepts in java.Create a linkedlist, read size of the list , read the elements for the linkedlist and display the index 1 elements from the linkedlist.


## ALGORITHM :
1. Start the program.

2. Create a Scanner object to take user input.

3. Read an integer n from the user (number of elements).

4. Initialize an empty LinkedList<String> named cars.
  
5. Use a loop from 0 to n-1 to read n strings and add each string to the cars list.

6. Retrieve the element at index 1 from the LinkedList using get(1).

7. Print the retrieved element with a descriptive message.
   
8.	End

## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        LinkedList<String> cars=new LinkedList<String>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++)
        {
            cars.add(sc.next());
        }
        
        System.out.println("Element at index 1 :"+cars.get(1));
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/e7e82b8c-01c2-4327-8db4-831990911cd5)


## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





