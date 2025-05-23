# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To create a Java Program to store a String Value in a file "testout.txt" using Data Output Stream.

## ALGORITHM :
1.  The program creates testout.txt and initializes FileOutputStream and DataOutputStream. It prompts the user to enter a string, writes it to testout.txt using writeUTF(), and then closes the streams.
2.	It reopens testout.txt with FileInputStream and DataInputStream, reads the stored string using readUTF(), displays it, and then closes the streams.
3.	It deletes testout.txt.
4.	After deletion, it tries to read an integer from testout.txt, which causes an error because the file no longer exists.
5.	The program catches and displays an IOException message if any file-related error occurs, including the attempt to read after deletion.


## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
FileOutputStream fos=new FileOutputStream("testout.txt");
DataOutputStream dos=new DataOutputStream(fos);
Scanner sc=new Scanner(System.in);
String str=sc.nextLine();
System.out.println("Successfully Completed");
dos.writeUTF(str);

dos.close();
fos.close();

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/5e1143c3-cf0c-465a-8342-ac64664ed1ec)


## RESULT:
Thus the Java Program to store a String Value in a file "testout.txt" using DataOutputStream was executed and verified successfully.

