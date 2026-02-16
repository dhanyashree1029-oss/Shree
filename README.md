import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter two numbers: ");
        double a = sc.nextDouble();
        double b = sc.nextDouble();

        if (b == 0) {
            System.out.println("Cannot divide by zero!");
        } else {
            double result = a / b;
            System.out.println("Result = " + result);
        }

        sc.close();
    }
}