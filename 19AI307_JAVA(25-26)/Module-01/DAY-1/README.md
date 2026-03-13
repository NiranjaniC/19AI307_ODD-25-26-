# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:


## AIM:
To develop a Java program that accepts a user's name, age, and favorite number as input and displays them using different output methods such as print(), println(), and printf() with formatted output.

## ALGORITHM :
1. Start the program.

2. Create a Scanner object to read input from the user.

3. Read the inputs:

4. Display the outputs using different print methods:

5. Close the Scanner and end the program.



## PROGRAM:
 ```
Program to implement variables and Operators using Java
Developed by: Niranjani.C
RegisterNumber: 212223220069 

```
```
import java.util.Scanner;
public class PrintStyles{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String name=sc.next();
        int age=sc.nextInt();
        float favnum=sc.nextFloat();
        System.out.print("Hello, "+name+"\n");
        System.out.println("You are "+age+" years old");
        System.out.printf("Your favorite number is %.2f",favnum);
        sc.close();
    }
}
```

## OUTPUT:



## RESULT:

