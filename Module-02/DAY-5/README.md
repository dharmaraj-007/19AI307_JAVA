# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
Develop a Java Program to sort the elements of an array in descending order.

## ALGORITHM :
STEP 1:Start the program.

STEP 2:Read the integer n representing the number of elements.

STEP 3:Create an Integer array arr of size n.

STEP 4:Read n integers from the user and store them in the array arr.

STEP 5:Sort the array arr in descending order using Arrays.sort with Collections.reverseOrder().

STEP 6:Print the message "Result of a Sorted Array :".

STEP 7:Display the elements of the sorted array separated by spaces.

STEP 8:End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo{
    public static void main(String[] args)
    {
      Scanner sc=new Scanner(System.in);
      int n=sc.nextInt();
      Integer[] arr=new Integer[n];
      
        System.out.print("Result of a Sorted Array :");
      for(int i=0;i<n;i++)
      {
          arr[i]=sc.nextInt();
      }
     Arrays.sort(arr,Collections.reverseOrder());
    for(int i=0;i<n;i++)
    {
         System.out.print(arr[i]+ " ");
    }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/0c9856ba-87cd-46ff-9756-ab1b3952f16a)

## RESULT:
Thus the java program to sort the elements of an array in descending order was executed successfully




