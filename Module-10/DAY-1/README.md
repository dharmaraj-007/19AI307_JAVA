# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
Create an arraylist and swap two elements in that arraylist.

## ALGORITHM:
1. Start the program.

2. Create a Scanner object to read input from the user.

3. Read an integer n, representing the number of elements to input.

4. Create an empty ArrayList of strings.

5. Use a loop to read n strings from the user and add each to the ArrayList.

6. Swap the elements at index 1 and index 3 in the ArrayList using Collections.swap().

7. Print the updated ArrayList to display the result.
8.	End

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
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
        ArrayList<String> al=new ArrayList<>();
        int n=sc.nextInt();
        for(int i=0;i<n;i++){
            al.add(sc.next());
        }
        Collections.swap(al,1,3);
        System.out.println(al);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/9b7008d5-7679-46b4-8370-a0ffe64e06db)


## RESULT:
Thus the Java Program to Create an arraylist and swap two elements in that arraylist was executed successfully.

