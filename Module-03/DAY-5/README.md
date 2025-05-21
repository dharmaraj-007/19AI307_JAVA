# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
Write a java program to replace the substring.

## ALGORITHM :
STEP 1:Start the program.

STEP 2:Create a Scanner object to read input from the user.

STEP 3:Read three strings from the user:

- str1: the main string

- str2: the substring to be replaced

- str3: the new substring to replace str2

STEP 4:Replace all occurrences of str2 in str1 with str3 using the replace() method.

STEP 5:Store the result in a new string variable res.

STEP 6:Print the resulting string with the message "Result: ".

STEP 7:End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
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
        String str1=sc.nextLine();
        String str2=sc.nextLine();
        String str3=sc.nextLine();
        String res=str1.replace(str2,str3);
        System.out.println("Result: "+res);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e528fb34-affa-4d85-a0ba-1fd69ce8c81c)


## RESULT:
Thus the  Java program to replace the substring was executed successfully

