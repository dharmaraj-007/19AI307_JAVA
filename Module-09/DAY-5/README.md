# Ex.No:9(E) STRING WRITER

## AIM:
To print the string "String Writer" to the output screen using StringWriter in Java.

## ALGORITHM :
1.Create an instance of StringWriter.
2.Use the write() method to write the string "String Writer" into the StringWriter object.
3.Retrieve the written content using the toString() method.
4.Print the retrieved content to the screen.

## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.io.StringWriter;

public class Main {
  public static void main(String[] args) {

    String data = "String Writer";

    try {
      StringWriter input=new StringWriter();
     
      System.out.println("Data in the StringWriter: "+data);
      
      
      
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/77c5eef6-a68b-4516-a581-1d0d07a3fc5b)

## RESULT:
The program successfully prints the string "String Writer" to the output screen using StringWriter, displaying: "Data in the StringWriter: String Writer."
