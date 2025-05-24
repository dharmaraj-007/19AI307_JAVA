# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To write a Java program that sorts a list of custom elements using the Comparator interface while utilizing LinkedList from Java Collections Framework.
## ALGORITHM :
1.Define a custom class (e.g., Person) with fields like name and age.  
2.Implement a custom Comparator to sort Person objects by age (or any chosen field).  
3.Create a LinkedList of Person objects.  
4.Use Collections.sort() with the custom comparator to sort the list.  
5.Print the sorted list.  


## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: DHARMARAJ S
RegisterNumber: 212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        LinkedList<Integer>t=new LinkedList<Integer>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.add(sc.nextInt());
        }
        t.sort(new Comparator<Integer>(){
            public int compare(Integer num1, Integer num2){
                return num1.compareTo(num2);
            }
        });
        for(Integer num : t){
            System.out.println(num);
        }
        }
    }
```

## OUTPUT:

![10](https://github.com/user-attachments/assets/5c384e71-05dd-4680-bbc1-c20e1d42b566)


## RESULT:
The program sorts the LinkedList of Person objects in ascending order of age using a custom Comparator and displays the sorted list.



