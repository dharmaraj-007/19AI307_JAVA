# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End

## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        String a=sc.nextLine();
        String b=sc.nextLine();
        StringBuffer s=new StringBuffer(a+" ");
        s.append(b);
        System.out.println(s);
    }
}
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/000aac11393a3cb57536a5957169942264188108/Module-03/DAY-2/1.png

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
