# Experiment-1---JAVA
## AIM
To create a Java Program to print the sum,difference,product,quotient and remainder of two numbers.
## PROCEDURE
1. Import the Scanner class from the java.util package.
2. Define a public class named "Main".
3. Declare the main method with the signature "public static void main(String[] args)".
4. Inside the main method, create an instance of the Scanner class using "Scanner sc = new Scanner(System.in)" to read input from the user.
5. Declare integer variables "add", "sub", "prod", "rem" to store the results of arithmetic operations.
6. Perform arithmetic operations and end the program.
## PROGRAM
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int add,sub,prod,rem;
        float divide;
        Scanner sc = new Scanner(System.in);
        int ab=sc.nextInt();
        int cd=sc.nextInt();
        add=ab+cd;
        sub=ab-cd;
        prod=ab*cd;
        divide=ab/cd;
        rem=ab%cd;
        System.out.println("Sum = "+add);
        System.out.println("Subtraction = "+sub);
        System.out.println("Product = "+prod);
        System.out.println("Division = "+divide);
        System.out.println("Remainder = "+rem);
    }
}
```
## OUTPUT
<img width="552" alt="image" src="https://github.com/Shavedha/Experiment-1---JAVA/assets/93427376/b85c14ef-5feb-4295-aa91-1a7720d0e174">

## RESULT
Hence Arithmetic operations are performed using Java Programming Language.
