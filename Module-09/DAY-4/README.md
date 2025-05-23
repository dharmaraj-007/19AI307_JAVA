# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
class Employeeinfo implements Serializable{
    String name;
    String desi;
    transient int id;
    Employeeinfo(String name,String desi,int id){
        this.name=name;
        this.desi=desi;
        this.id=id;
    }
}
```
## OUTPUT:


![image](https://github.com/user-attachments/assets/66d74608-0840-4c7a-bf1d-b930f50aca19)


## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

