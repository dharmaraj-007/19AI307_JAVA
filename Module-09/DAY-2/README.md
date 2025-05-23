# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To create a java program to write data using ByteArrayOutputStream.


## ALGORITHM :
1.	The user enters a string (data), followed by two integers (start and length) specifying the starting position and number of characters to write.
2.	The string data is converted to a byte array (array).
3.	Using ByteArrayOutputStream, it writes length bytes from array, starting at start.
4.	The written data is retrieved as a string (streamData) and displayed, showing the original input and the specific segment written to the stream.
5.	Any exceptions are caught and handled, displaying stack trace information if an error occurs.




## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.io.ByteArrayOutputStream;
import java.util.*;
public class Main {
  public static void main(String[] args) 
  {
       Scanner sc=new Scanner(System.in);
      String in=sc.nextLine();
      try
      {
          ByteArrayOutputStream bos=new ByteArrayOutputStream();
          byte b[]=in.getBytes();
          bos.write(b);
          System.out.println("Output stream: "+bos.toString());
  
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/398d9e55-aacb-488c-81a4-e49dc3a0aa35)


## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





