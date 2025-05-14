# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To read a double value from a file "OutputFile.txt" using DataInputStream and the predefined function readDouble().

## ALGORITHM :
```
1.Create a FileInputStream object for "OutputFile.txt".
2.Wrap it in a DataInputStream.
3.Use readDouble() to read the double value from the file.
4.Print the value.
5.Close the stream.
```

## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
FileInputStream input=new FileInputStream("OutputFile.txt");
DataInputStream di=new DataInputStream(input);
double data=di.readDouble();
System.out.println(data);
input.close();
di.close();
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/7c199ea0-778d-4e03-8172-7e44072b990e)

## RESULT:
The program successfully reads and displays a double value from "OutputFile.txt" using the readDouble() method of DataInputStream.

