# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
To create a Class with Name, Id, and a final Year variable, and to print the member variables in the output using a Main class.
  
## ALGORITHM :
1.Define a final class Class with three member variables: Name, Id, and Year.
2.Make Year a constant with the value "3rd Year".
3.Create a constructor to initialize Name and Id.
4.Implement a print() method to display the Name, Id, and Year.
5.Create a Main class to instantiate and access the print() method of Class.



## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Company{
    String name;
    String Id;
    final String year;
    Company(String na,String id,String year){
        this.name=na;
        this.Id=id;
        this.year=year;
    }
    void print(){
        System.out.println("Student Details are, \nId is "+this.Id+"\nName is "+this.name+"\nYear of Studying is "+this.year);
    }
    }
    public class Main{
        public static void main(String[] args){
            Company obj=new Company("David","S201","3th Year");
            obj.print();
        }
    }
   
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/41c4a632-b501-4184-8bdb-dc8a7cb68d0f)

## RESULT:
The program displays "Name: David, Id: S201, Year: 3rd Year" in the output.
