# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To write a Java program that writes a specified number of bytes from a string to a file (testout.txt) using OutputStream, based on user input.

## ALGORITHM :
1.Import necessary I/O and utility classes.  
2.Define a string str = "HI EVERYBODY...".  
3.Convert the string to a byte array using getBytes().  
4.Read the number of bytes to write from the user.  
5.Create a FileOutputStream for testout.txt.  
6.Write the specified number of bytes from the byte array to the file.  
7.Close the stream.


## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
OutputStream fout=new FileOutputStream("testout.txt");
String s="HI EVERYBODY...";
byte b[]=s.getBytes();
Scanner sc=new Scanner(System.in);
int start=sc.nextInt();
int length=sc.nextInt();
fout.write(b,start,length);
fout.close();
System.out.println("Successfully Completed");
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/913134c5-c8bb-4951-9328-af89fb6cccfc)

## RESULT:
Thus the implementation of a Java Program to write a String in a file "testout.txt" using FileOutputStream was executed and verified successfully

