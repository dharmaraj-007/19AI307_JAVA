# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To store student details (name, department) in a file "student.txt" using serialization by creating an object of the Studentinfo class and serializing it.
## ALGORITHM :
1.Define the Studentinfo class that implements the Serializable interface.  
2.Create an instance of Studentinfo using the user-provided name and department.  
3.Serialize the object and write it to "student.txt" using ObjectOutputStream.  
4.Close the stream after serialization.  

## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
try
{
    Scanner sc=new Scanner(System.in);
    String name=sc.nextLine();
    String dept=sc.nextLine();
    Studentinfo si1=new Studentinfo(name,dept);
    FileOutputStream fos=new FileOutputStream("student.txt");
    ObjectOutputStream oos=new ObjectOutputStream(fos);
    oos.writeObject(si1);
    oos.close();
}
catch(Exception e){
    System.out.println(e);
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/67a55eb1-5902-4f5b-86da-3b89fb945707)


## RESULT:
The program successfully reads student details (name and department) from the user, creates a Studentinfo object, and serializes it to the file "student.txt".
