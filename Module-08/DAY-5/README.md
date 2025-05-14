# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program that reads content from a user-input string using the Reader class and displays it using a predefined method.

## ALGORITHM :
1.Import java.io.* and java.util.Scanner.
2.Read a string input from the user using Scanner.
3.Create a CharArrayReader or StringReader to read from the string.
4.Initialize a char[] array = new char[12];.
5.Use the read(char[] cbuf) method to read characters from the string into the array.
6.Display the contents of the character array.
7.Close the reader.

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: Bala R
RegisterNumber:  212222220007
*/
```

## Sourcecode.java:
```
import java.io.*;
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String s=sc.nextLine();
        char[]array=new char[12];
        try{
            Reader input=new StringReader(s);
            input.read(array);
            System.out.println("Data read from the string:");
            System.out.println(array);
        }
        catch(Exception e){
            e.getStackTrace();
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a0064241-f794-4691-bd28-69a817570a1d)

## RESULT:
The program reads and displays part of the user-input string using a Reader and predefined read method.

