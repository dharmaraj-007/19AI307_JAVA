# Ex.No:10(E)  JAVA LINKED LIST

## AIM:
Create a linkedlist, read size of the list , read the elements for the linkedlist and display the elements from the linkedlist.Apply the Collection Concepts in java.
## ALGORITHM :
1. Start the program and create a Scanner object to read input from the user.

2. Initialize a LinkedList of String type to store elements.

3. Read the total number of elements (n) the user wants to enter.

4. Consume the leftover newline after reading the integer n to avoid input skipping.

5. Use a loop to read n string elements from the user using nextLine() and add each string to the LinkedList.

6. After the loop, print the entire LinkedList.

7. End the program.
## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: DHARMARAJ S
RegisterNumber: 212222240025 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        LinkedList<String> ll=new LinkedList<>();
        int n=sc.nextInt();
        sc.nextLine();
        for(int i=0;i<n;i++){
            String ele=sc.nextLine();
            ll.add(ele);
        }
        System.out.println(ll);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/157dd230-fb43-4287-b600-823bccb71d06)


## RESULT:

Thus the java program was successfully create a linkedlist, read size of the list , read the elements for the linkedlist and display the elements from the linkedlist. 
