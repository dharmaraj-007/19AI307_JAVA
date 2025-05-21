# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:

Write a java program to Read input ,split word from sentence and use string builder.

## ALGORITHM :
STEP 1:Start the program.

STEP 2:Read a line of input from the user using a Scanner.

STEP 3:Create a StringBuilder object using the input string.

STEP 4:Convert the StringBuilder object back to a String using the toString() method.

STEP 5:Split the string into words using the split("\\s") method (splits by whitespace).

STEP 6:Iterate through each word in the resulting array.

STEP 7:Print each word on a new line.

STEP 8:End of the program.

## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
	public class Main{  
	public static void main(String args[]){  
	Scanner sc = new Scanner(System.in);  
	String str=sc.nextLine();
 StringBuilder sb=new StringBuilder(str);
 String str1=sb.toString();
	String[] words=str1.split("\\s");
	for(String w:words){  
	System.out.println(w);  
	}  
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/416e2ac6-9ab3-4f0d-8dc6-d70ba5551435)



## RESULT:
Thus the java program to Read input ,split word from sentence and use string builder was executed successfully.



