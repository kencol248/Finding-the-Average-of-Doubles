// Kenyah Collins, 1/23/2023, Lab 1 - Find the average of three doubles

import java.util.*;

public class Main {
    private static Scanner input = new Scanner(System.in);

    public static void main(String[] args) {
//title
        System.out.println("\tFinding the average of three numbers");
        System.out.println();

//user input for three numbers, all doubled
        double firstNumber;
        double secondNumber;
        double thirdNumber;

        System.out.print("Enter the first number: ");
        firstNumber = input.nextDouble();
        System.out.println();

        System.out.print("Enter the second number: ");
        secondNumber = input.nextDouble();
        System.out.println();

        System.out.print("Enter the third number: ");
        thirdNumber = input.nextDouble();
        System.out.println();

// created a variable to find the average of the three doubles the user put
        double average = (firstNumber + secondNumber + thirdNumber) / 3.0;

// output information to user all rounded two decimal places
    System.out.printf("The average of %.2f, %.2f and %.2f is %.2f", firstNumber, secondNumber, thirdNumber, average);
    }
}
