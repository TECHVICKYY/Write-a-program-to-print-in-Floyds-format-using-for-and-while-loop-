# Write-a-program-to-print-in-Floyds-format-using-for-and-while-loop-
import java.util.*;
import java.util.Scanner;

public class A1_Ex8 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Enter the number of rows in Floyd's triangle:");
				 Scanner sc = new Scanner(System.in);
				 int num = sc.nextInt();
				 for(int i=1;i<=num;i++) {
				 int j=1;
				 while(i>=j) {
				 System.out.print("* ");
				 j++;
				 }
				 System.out.print("\n");
				 }
				}
	}
