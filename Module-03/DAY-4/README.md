# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To write a Java program that reads a string input and prints the tokens separated by a comma (,) using the nextToken() method of the StringTokenizer class.

## ALGORITHM :
1.Start the program.  
2.Import java.util.StringTokenizer. 
3.Read an input string containing words or phrases separated by commas.  
4.Create a StringTokenizer object with the input string and comma (,) as the delimiter.  
5.Loop through the tokens using the hasMoreTokens() and nextToken() methods.  
6.Print each token.  
7.End the program.  


## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: Bala R
RegisterNumber:212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Main {  
   public static void main(String[] args) {
       Scanner sb=new Scanner(System.in);
       String str1=sb.nextLine();
       String delimiter=",";
       StringTokenizer st = new StringTokenizer(str1,delimiter);  
       if(st.hasMoreTokens()){
           System.out.println("Next token is : " + st.nextToken()); 
       }
        
      
        
   }      
}  
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e513f5b6-cf05-4d6e-bb6d-09bd5cf08773)


## RESULT:
The program successfully extracted and printed the tokens "apple", "banana", "mango", and "grape" from the input string using the nextToken() method of StringTokenizer.
