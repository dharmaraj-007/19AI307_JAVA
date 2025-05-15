# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To implement a Java program that writes a string to a file named "testout.txt" using the Writer class.
## ALGORITHM :
1.Import java.io.* package.
2.Define the string str = "Welcome to Java File Concept -Reader".
3.Create a Writer object (e.g., FileWriter) pointing to "testout.txt".
4.Use write() method to write the string to the file.
5.Close the writer using close().

## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: Bala R
RegisterNumber:  212222220007
*/
```

## Sourcecode.java:
```
Writer w=new FileWriter("testout.txt");
String content="Welcome to Java File Concept -Reader";
w.write(content);
w.close();
System.out.println("Wrote File Successfully");
```

## OUTPUT:
![6](https://github.com/user-attachments/assets/f915645d-f364-4874-871e-581a9628cc13)


## RESULT:
The program writes the specified string to the file testout.txt using Writer.




