# Ex.No:9(C)             STRING READER
## AIM:
 To Create a Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.  The user enters a string (data) and an integer (skipnumber) indicating the number of characters to skip.
2.	The original string is displayed for reference.
3.	A StringReader object, input, is created to read from data.
4.	The program skips the specified number of characters (skipnumber) in the string.
5.	It reads and displays the remaining characters one by one until the end of the string.
6.	Any exceptions are caught, and stack trace information is generated if an error occurs.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.io.*;
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String str=sc.nextLine();
        try{
            StringReader sr=new StringReader(str);
            sr.skip(5);
            System.out.println("Original data: "+str);
            int i=0;
            System.out.println("Data after skipping");
            while((i=sr.read())!=-1){
                System.out.print((char)i);
            }
            sr.close();
        }
        catch(Exception e) {
      e.getStackTrace();
    }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/3c277647-6547-46ca-9fe8-d4be0d403bfc)


## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.

