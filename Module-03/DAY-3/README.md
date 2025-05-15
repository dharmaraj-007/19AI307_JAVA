# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To write a Java program to demonstrate a mutable string using StringBuilder by modifying the content of the same object.

## ALGORITHM :
1.Start the program.  
2.Create a StringBuilder object with an initial string.  
3.Display the original string.  
4.Modify the string using StringBuilder methods such as append, insert, replace, or delete.  
5.Display the updated string (modified within the same object).  
6.End the program.  

## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class MutableStringEx { 
public static void main(String[ ] args) 
{ 
 Scanner sc=new Scanner(System.in);
 String str=sc.nextLine();
 StringBuilder sb=new StringBuilder(str);
  
  sb.append(" Easy");
  sb.append(" today");
  System.out.println(sb.toString()); 
 } 
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/7c42ecc7-bc7e-4708-80ae-c5e12c9db101)

## RESULT:
Thus, the Java program used the replace() method to replace the given string from the specified beginIndex and endIndex,and used StringBuilder to demonstrate mutability. The program was executed successfully.









