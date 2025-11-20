# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a magical building, an elevator behaves oddly:
If the floor number is divisible by 3 and 5, it says "Skipped".
If the floor number is divisible by 3 only, it says "Beware!".
If the floor number is divisible by 5 only, it says "Blessings!".
Otherwise, it announces the floor number - print - "Floor {number}" .

## AIM:
Write a Java program to simulate this elevator logic for a given floor number.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Check if the floor number is divisible by both 3 and 5 If yes, print "Skipped".
4.	Else, check if the floor number is divisible by 3  If yes, print "Beware!".
5.	Else, check if the floor number is divisible by 5 If yes, print "Blessings!".
6.	End

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: HEMAPRIYA R
RegisterNumber:  212222040055
*/
```

## SOURCE CODE:
```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int floor = sc.nextInt(); 
        
        if (floor % 3 == 0 && floor % 5 == 0) {
            System.out.println("Skipped");
        } 
        else if (floor % 3 == 0) {
            System.out.println("Beware!");
        } 
        else if (floor % 5 == 0) {
            System.out.println("Blessings!");
        } 
        else {
            System.out.println("Floor " + floor);
        }
    }
}
```
## OUTPUT:
<img width="1289" height="396" alt="image" src="https://github.com/user-attachments/assets/74c805ff-9db0-483f-b297-9e88bf75af93" />

## RESULT:
The program has been executed successfully and the desired output has been obtained.

