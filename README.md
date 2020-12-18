# Add
import java.util.Scanner;

public class Add {
	public static void main(String[] args) {
		Scanner input= new Scanner(System.in); 
		int num1;
		int num2;
		int sum;
		System.out.println("Enter frist number");
		num1 = input.nextInt();
		System.out.println("Enter seconde number");
		num2 = input.nextInt();
		
		sum = num1 + num2;
		System.out.printf("The sum of frist and second number is %d%n2  ", sum);
		
		
	}

}
