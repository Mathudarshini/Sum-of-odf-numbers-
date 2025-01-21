# Sum-of-odf-numbers-
import java.util.Scanner;
public class SumOfOddNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the range (positive integer): ");
        int n = scanner.nextInt();
        int sum = 0;
        for (int i = 1; i <= n; i++) {
            if (i % 2 != 0) { 
                sum += i;
            }
        }
        System.out.println("The sum of odd numbers from 1 to " + n + " is: " + sum);
        scanner.close();
    }
}

output:
Enter the range (positive integer): 10
The sum of odd numbers from 1 to 10 is: 25# Sum-of-odf-numbers-
