# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To demonstrate the control flow of try-catch-finally in Java when an ArrayIndexOutOfBoundsException occurs in the try block and is handled in the catch block.

## ALGORITHM :
1.Declare and initialize an integer array.
2.Use a try block to access an invalid array index (causing ArrayIndexOutOfBoundsException).
3.Catch the exception in a catch block and display an error message.
4.Use a finally block to print a statement that executes regardless of the exception.
5.Execute the program to observe the flow through try, catch, and finally.

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
     
        int[] arr = new int[4];
         
        try
        {
           int i=arr[4];
           System.out.println("Inside try block");
        }
        catch(ArrayIndexOutOfBoundsException ex){
            System.out.println("Exception caught in catch block");
        }
        finally
        {
            System.out.println("finally block executed");
        }
         
        
      
        System.out.println("Outside try-catch-finally clause");
    }
}
```

## OUTPUT:

![5](https://github.com/user-attachments/assets/5dafc109-edfd-480d-b0dd-f1ef64333e87)


## RESULT:
The program shows that the catch block handles the exception and the finally block always executes.

