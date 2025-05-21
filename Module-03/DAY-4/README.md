# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:

Write a java program to calculates the number of tokens present in the tokenizer String.

## ALGORITHM :
STEP 1:Start the program.

STEP 2:Define a string str with the value "Hello Everyone Have a nice day".

STEP 3:Create a StringTokenizer object using the string str as input.

STEP 4:Count the number of tokens using the countTokens() method.

STEP 5:Store the count in a variable token.

STEP 6:Display the total number of tokens using System.out.println.

STEP 7:End the program.




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public  class Demo{
    public static void main(String[] args)
    {
        String str="Hello Everyone Have a nice day";
        StringTokenizer input=new StringTokenizer(str);
        int token=input.countTokens();
        System.out.println("Total number of Tokens: "+token);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/bda416da-297f-441d-94c3-24cd5b25cf50)


## RESULT:
Thus the java program to calculates the number of tokens present in the tokenizer String was executed successfully.
