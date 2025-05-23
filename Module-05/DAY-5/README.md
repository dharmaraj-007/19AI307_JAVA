# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To create a Java program that reads the student's name and ID at runtime using getter and setter methods, and displays them.
## ALGORITHM :
1.Create a Student class with private fields name and id.  
2.Provide setter and getter methods for both name and id.  
3.In the Main class, use Scanner to read the name and ID from the user at runtime.  
4.Set the values using the setter methods and display them using the getter methods.  


## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: DHARMARAJ S
RegisterNumber: 212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
class detail{
    private String name;
    private int id;
    public void setIn(String name,int id){
        this.name=name;
        this.id=id;
    }
    public void getIn(){
        System.out.println(name);
        System.out.println(id);
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String name=sc.nextLine();
        int id=sc.nextInt();
        detail obj=new detail();
        obj.setIn(name,id);
        obj.getIn();
        
        
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/770d3ea8-5cce-470f-acaa-8152c9917878)

## RESULT:
Thus Java program that reads the student's name and ID at runtime using getter and setter methods, and displays was executed successfully
