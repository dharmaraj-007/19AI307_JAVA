# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
Develop a Java Program to read and print two dimensional array (Matrix).

## ALGORITHM :

STEP 1:Start the program.

STEP 2:Read the number of rows (rows) and columns (cols) from the user.

STEP 3:Create a 2D integer array mat of size rows x cols.

STEP 4:Use nested loops to input elements into the matrix:
- Outer loop runs from i = 0 to rows - 1
  
- Inner loop runs from j = 0 to cols - 1

- Read element and store in mat[i][j]

STEP 5:Print the message "The Array is :".

STEP 6:Use nested loops to display the matrix elements:

- Outer loop runs from i = 0 to rows - 1

- Inner loop runs from j = 0 to cols - 1

- Print each element mat[i][j] followed by spaces

- After each row, print a new line

STEP 7:End the program.

## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: DHARAMRAJ S
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
        int rows=sc.nextInt();
        int cols=sc.nextInt();
        int[][] mat=new int[rows][cols];
        System.out.println("The Array is :");
        for(int i=0;i<rows;i++)
        {
            for(int j=0;j<cols;j++)
            {
                mat[i][j]=sc.nextInt();
            }
        }
        for(int i=0;i<rows;i++)
        {
            for(int j=0;j<cols;j++)
            {
                System.out.print(mat[i][j]+ "  ");
            }
            System.out.println();
        }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/00fb2a88-e4e2-4d86-8ef0-c9b57b9d1167)

## RESULT:
Thus the java program to read and print two dimensional array (Matrix) has been executed successfully.


