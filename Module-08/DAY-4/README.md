# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```

      FileInputStream fir=new FileInputStream("sample.txt");
      BufferedInputStream bir=new BufferedInputStream(fir);
      Scanner sc=new Scanner(System.in);
      int n=sc.nextInt();
      bir.skip(n);
      int a=0;
      System.out.println("Contents after skipping "+n+" bytes:");
      while((a=bir.read())!=-1){
          System.out.print((char)a);
      }
      bir.close();
      fir.close();
             
 
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/792d5af8-4e3a-470e-8f94-5c2a144fdc3c)


## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


