Import java.util.Scanner;
 class Operator { public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 // Input values 
System.out.print("Enter first number (a): ");
 int a = scanner.nextInt(); int b = scanner.nextInt(); 
// Arithmetic 
System.out.println("Addition: " + (a + b));
 System.out.print("Enter second number (b): ");

 System.out.println("Multiplication: " + (a * b));
 // Relational
 System.out.println("a > b: " + (a > b));
 // Logical 
System.out.println("Both are positive: " + (a > 0 && b > 0));
 // Ternary 
System.out.println("Max: " + (a > b ? a : b)); scanner.close();
 } 
}
OUTPUT:
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> javac hello.java
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> java hello.java
Enter first number (a): 6
Enter second number (b): 8
Addition: 14
Multiplication: 48
a > b: false
Both are positive: true
 1> Max: 8
PS C:\Users\MY\OneDrive\Pictures\Documents \



