# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Employee with method display(). Inside display(), return the current object using this. Create another method that calls display().printName()

## AIM:
To Create a class Employee with method display(). Inside display(), return the current object using this.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create the method setName() to store the employee name.
4.	Create the method display() that returns the current object using this.
5.	Create the method printName() to print the employee name.
6.	In the main() method, read the employee name using Scanner.
7.	Create an Employee object, set the name using setName(), and call display() to return the same object.
8.	Call printName() to display the name and end the program.
   
## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: HEMAPRIYA R
RegisterNumber: 212222040055
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class Employee {
    String name;

    void setName(String name) {
        this.name = name; 
    }

    Employee display() {
        return this; 
    }

    void printName() {
        System.out.println("Employee Name: " + name);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String empName = sc.nextLine();

        Employee e1 = new Employee();
        e1.setName(empName);
        e1.display().printName(); 
    }
}
```

## OUTPUT:
<img width="1234" height="360" alt="image" src="https://github.com/user-attachments/assets/15cea4a6-f850-43e7-ac73-c877b1ba854b" />

## RESULT:
The program has been executed successfully and the desired output has been obtained.

