# Ex.No:8(C)             FILTER READER
## AIM:
 To create a java Program to read the content from the file by using Filter Reader 


## ALGORITHM :
1.Import necessary I/O classes (FileInputStream, FilterInputStream, BufferedInputStream).
2.Create a FileInputStream for the file "sample.txt".
3.Wrap it with a BufferedInputStream (a subclass of FilterInputStream).
4.Read the contents byte by byte and cast them to characters.
5.Display the characters until the end of the file is reached.
6.Close the stream.

## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by: Bala R
RegisterNumber: 212222220007 
*/
```

## Sourcecode.java:
```
FileInputStream file1=new FileInputStream("sample.txt");
FilterInputStream filter=new BufferedInputStream(file1);
int k=0;
while((k=filter.read())!=-1){
    System.out.print((char)k);
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1cc7db77-62d7-4e4c-9372-bb77d30b95d7)

## RESULT:
Thus the java Program to read the content from the file by using Filter Reader  was executed and verified successfully.









