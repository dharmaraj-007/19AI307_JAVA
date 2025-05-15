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
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
FileOutputStream fout1=new FileOutputStream("F1.txt");
FileOutputStream fout2=new FileOutputStream("F2.txt");
ByteArrayOutputStream bout=new ByteArrayOutputStream();
bout.write(69);
bout.writeTo(fout1);
bout.writeTo(fout2);
bout.close();
System.out.println("Success...");
```

## OUTPUT:
![7](https://github.com/user-attachments/assets/7fb78f3b-9e2e-45fe-b22d-369dd120daed)


## RESULT:
Thus, java program to write data using ByteArrayOutputStream was executed and verified successfully.





