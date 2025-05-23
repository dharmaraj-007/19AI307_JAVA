# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
File 1
package pack;

public class A {
    public void msg() {
        System.out.println("Hello from class A in package pack.");
    }
}
File 2
package mypack;

import pack.A;

public class B {
    public static void main(String[] args) {
        A a = new A();
        a.msg();
    }
}
```

## OUTPUT:

Hello from class A in package pack.

## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

