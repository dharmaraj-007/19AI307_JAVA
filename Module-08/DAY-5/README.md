# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
Write a Java Program to read the content from the String using Reader

## ALGORITHM :
1.Start the program.

2.Create a Scanner object to read a line of input from the user.

3.Store the input string in a variable (str), and initialize a character array of size 40 to hold the characters read from the string.

4.Create a StringReader object, passing the input string to its constructor.

5.Use the read() method of Reader to read the string into the character array.

6.Print the contents of the character array to show the data read from the string.

7.Close the reader and handle any IOException using a try-catch block.

8.End the program.


## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
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
        char[] arr=new char[40];
        try{
            Reader reader=new StringReader(str);
            reader.read(arr);
            System.out.println("Data read from the string:");
            System.out.println(arr);
            reader.close();
        }
        catch(IOException e){
            e.printStackTrace();
        }
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/5d7c59f0-1373-48e4-9170-874027b91edf)


## RESULT:
Thus, the java program to write a Java Program to read the content from the String using Reader was executed successfully
 

