# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
Develop a Java Program to sort the elements of an array in ascending order.

## ALGORITHM :
1.Start the program.  
2.Declare and initialize an array with unsorted elements.  
3.Use a sorting algorithm (like Bubble Sort) to arrange the elements in ascending order:  
4.Compare each element with the next one.  
5.Swap them if they are in the wrong order.  
6.Repeat the process until the array is sorted.  
7.Display the sorted array.  
8.End the program.  

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.Arrays;
import java.util.Scanner;
public class SortedArray{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int size=sc.nextInt();
        int[]arr=new int[size];
        for(int i=0;i<size;i++){
            arr[i]=sc.nextInt();
        }
        Arrays.sort(arr);
        System.out.println("Result of a Sorted Array :");
        for(int i=0;i<size;i++){
            System.out.print(arr[i]+"  ");
        }
    }
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/309ebcce-5ccd-478b-8e3a-1af2c72876b6)


## RESULT:

The Java program successfully sorted the array in ascending order using the Bubble Sort algorithm.


