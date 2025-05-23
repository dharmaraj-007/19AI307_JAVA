# Ex.No:9(E) STRING WRITER

## AIM:
Write a Java Program to print the string "This is the text in the string." in the outputscreen using StringWriter

## ALGORITHM :

1. Start the program.

2. Create a String variable named data and assign it the text "This is the text in the string.".

3. Use a try-catch block to handle potential exceptions during string writing.

4. Inside the try block, create a StringWriter object.

5. Write the data string to the StringWriter using the write() method.

6. Print the contents of the StringWriter to the console.

7. Close the StringWriter using the close() method and handle exceptions if any occur.
   
8.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.io.StringWriter;

public class Main {
  public static void main(String[] args) {

    String data = "This is the text in the string.";

    try {
      StringWriter w=new StringWriter();
      w.write(data);
      System.out.println("Data in the StringWriter: "+w);
      w.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/1dea4c22-2035-4dae-98c7-65a8a08e0de9)


## RESULT:
Thus, implementation of  a Java program was successfully to print the string "This is the text in the string." in the outputscreen using StringWriter


