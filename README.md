# Java Cheat Sheet
Comprehensive **Java Programming** Guide With **Mini Projects** | Best for people, who are coming from other programming language or Just want a **quick Refresh**

## Topics Covered

1. HelloWorld Program
2. Comments In Java
3. Print Methods In Java
4. Variables In Java
5. DataTypes In Java
6. Operators In Java
7. Type Casting In Java
8. Taking Input from User In Java 
9. Strings & Its Function In Java	 		 
10. Math Class In Java
11. Conditions In Java  
12. Loop In Java       
13. Arrays In Java      
14. Try-catch In Java  

## PDF 

[Java Cheat Sheet](https://github.com/Technowlogy-Pushpender/Java-Cheat-Sheet/blob/master/java-cheat-sheet-comprehensive-guide.pdf)

## Mini Projects 

* Multi Operator Calculator

```
import java.util.Scanner;

public class Main {
	public static void main(String[] args) {
	
		String choice = "yes";
		while(choice == "yes") {
			System.out.println("\n\n[?] Enter 1st Number :");
			Scanner scan = new Scanner(System.in);
			float num1 = scan.nextInt();
			
			System.out.println("[?] Enter 2nd Number :");
			float num2 = scan.nextInt();
			
			System.out.println("[Choose From List] : \n\t(M)ultiply\n\t(D)ivide\n\t(S)um\n\t(Su)btract\n");
			Scanner scan1 = new Scanner(System.in);
			String operator = scan1.nextLine();
			operator = operator.toLowerCase();
			
			switch(operator) {
				case "m":
					System.out.print("[+] Multiple of 1st & 2nd is ");
					System.out.print(num1 * num2);
					break;

				case "d":
					System.out.print("[+] Divide of 1st & 2nd is ");
					System.out.print(num1 / num2);
					break;

				case "s":
					System.out.print("[+] Sum of 1st & 2nd is ");
					System.out.print(num1 + num2);
					break;

				case "su":
					System.out.print("Subtract of 1st & 2nd is ");
					System.out.print(num1 - num2);
					break;

				default:
					System.out.println("Invalid Input !");
					
			} // switch
			
		} // While Loop
	
	} // main()

} // Main()
```
