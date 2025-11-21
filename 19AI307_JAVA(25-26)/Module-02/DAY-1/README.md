# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Vehicle with attributes as number, type and owner.
## AIM:
To Create a class Vehicle with attributes as number, type and owner.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class named Vehicle with the following data members:
4.	Create the first vehicle object v1.
5.	Create the second vehicle object v2.
6.	Display the details of v1 in the format:  number | type | owner
7.	End

## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: HEMAPRIYA R
RegisterNumber:  212222040055
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
class Vehicle{
    String number;
    String type;
    String owner;
}
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vehicle v1 = new Vehicle();
        v1.number = sc.next();
        v1.type = sc.next();
        v1.owner = sc.next();

        Vehicle v2 = new Vehicle();
        v2.number = sc.next();
        v2.type = sc.next();
        v2.owner = sc.next();

        System.out.println(v1.number + " | " + v1.type + " | " + v1.owner);
        System.out.println(v2.number + " | " + v2.type + " | " + v2.owner);

        sc.close();
    }
}
```

## OUTPUT:
<img width="1239" height="359" alt="image" src="https://github.com/user-attachments/assets/2f5b1d01-400f-4d8f-9d5a-ec09d4e28870" />

## RESULT:
The program has been executed successfully and the desired output has been obtained.


