# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to count Even and Odd Numbers in an Array.
<img width="1016" height="273" alt="image" src="https://github.com/user-attachments/assets/85fc9dec-e6c2-4083-aaca-763dc996581e" />


## AIM:
To Write a Java Program to count Even and Odd Numbers in an Array.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an integer array of size size.
4.	Initialize two counters: even = 0 and odd = 0.
5.	If arr[i] % 2 == 0, increment even by 1.
6.	Else, increment odd by 1.
7.	End.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: HEMAPRIYA R
RegisterNumber: 212222040055
*/
```

## SOURCE CODE:
```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        int arr[]=new int[size];
        for(int i=0;i<size;i++){
            arr[i]=sc.nextInt();
            
        }
        int odd=0;
        int even=0;
        for(int i=0;i<size;i++){
            if(arr[i]%2==0){
                even++;
            }
            else{
                odd++;
            }
        }
        System.out.println("Number of even elements: "+even);
        System.out.println("Number of odd elements: "+odd);
    }
}
```
## OUTPUT:
<img width="1285" height="692" alt="image" src="https://github.com/user-attachments/assets/b5c58b2f-543d-4d56-8e2d-e6b0c8c543ac" />

## RESULT:
Therefore the program successfully print the count of even and odd number for the given element.



