
# EX 1A Print All Numbers 
## DATE: 07/08/2025
## AIM:
To write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line.

## Algorithm
1.Start the program.
2. Create a Scanner object to read input from the user.
3. Read an integer input N.
4. If N is less than or equal to 0, display "Invalid input. N must be greater than 0.".
5. Otherwise, use a for loop to print all numbers from 1 to N, separated by spaces.
6. End the program.

## Program:
```
/*
Program to print all numbers from 1 to N
Developed by: Joel John Jobinse
Register Number:  212223240062
*/
import java.util.*;
public class PrintNum {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        if (n <= 0) {
            System.out.println("Invalid input. N must be greater than 0.");
        } else {
            for (int i = 1; i <= n; i++) {
                System.out.print(i + " ");
            }
        }
    }
}

```

## Output:
<img width="481" height="180" alt="image" src="https://github.com/user-attachments/assets/7a941f41-ef69-447a-be31-2a46cb0db6c3" />



## Result:
The program successfully print all the numbers from 1 to N. 
