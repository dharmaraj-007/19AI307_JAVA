# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that reads a sentence, splits it into individual words, and prints each word using a StringBuilder to demonstrate string manipulation.

## ALGORITHM :
1.Read Input: Take a sentence as input from the user.  
2.Split the Sentence: Use the split() method of the String class to separate the sentence into words.  
3.Create a StringBuilder: Use StringBuilder to store and manipulate each word.  
4.Loop through the Words: Iterate through each word and append it to the StringBuilder.  
5.Print Each Word: Print each word stored in the StringBuilder.  
6.End the Program  


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        String s=sc.nextLine();
        String[]word=s.split(" ");
        for(String w:word){
            System.out.println(w);
        }
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/bfa3c200-303f-4588-8692-490c7a3a0198)

## RESULT:
The program successfully splits the input sentence "very good" into individual words and prints "very" and "good" using StringBuilder.
