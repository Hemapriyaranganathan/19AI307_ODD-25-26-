# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
Write a Java program to create a class called Person with private instance variables name, age. and country. Provide public getter and setter methods to access and modify these variables.

## AIM:
To write a Java program to create a class called Person with private instance variables name, age. and country. Provide public getter and setter methods to access and modify these variables.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class with private variables: name, age, country, and create getter and setter methods for each.
4.	Define setter and getter methods
5.	Set the values to the object using setName(), setAge(), and setCountry().
6.	End

## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: HEMAPRIYA R
RegisterNumber:  212222040055
*/
```

## SOURCE CODE:
```
import java.util.*;
public class prog {
    private String name;
    private int age;
    private String country;
    public String getName() {
        return name;
    }
    public void setName(String name) {
        this.name = name;
    }
     public int getAge() {
         return age;
         }
     public void setAge(int age) {
         this.age = age;
         }
     public String getCountry() {
         return country;
         }
     public void setCountry(String country) {
         this.country = country;
         }


        public static void main(String[] args){
            
            Scanner s=new Scanner(System.in);
            prog per=new prog();
            String name=s.nextLine();
            int age=s.nextInt();
            s.nextLine();
            String country=s.nextLine();
            per.setName(name);
            per.setAge(age);
            per.setCountry(country);
            System.out.println("Person 1");
            System.out.println("Name: "+per.getName());
            System.out.println("Age: "+per.getAge());
            System.out.println("Country: "+per.getCountry());
        }
}
```
## OUTPUT:
<img width="1239" height="568" alt="image" src="https://github.com/user-attachments/assets/596ab96e-032b-4b9b-8de3-9942cbb087cf" />

## RESULT:
The program has been executed successfully and the desired output has been obtained.

