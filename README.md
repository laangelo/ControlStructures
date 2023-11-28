import java.util.Scanner;

public class CombinedControlStructures {
public static void main(String[] args) {
// Example of if-else statement
Scanner scanner = new Scanner(System.in);
System.out.print("Enter a number: ");
int userInput = scanner.nextInt();

if (userInput % 2 == 0) {
System.out.println("The number is even.");
} else {
System.out.println("The number is odd.");
}
// Example of switch statement
switch (userInput) {
case 1:
System.out.println("One");
break;
case 2:
System.out.println("Two");
break;
case 3:
System.out.println("Three");
break;
default:
System.out.println("Number is not 1, 2, or 3.");
}

// Example of a for loop
System.out.println("Counting from 1 to 5 using a for loop:");
for (int i = 1; i <= 5; i++) {
System.out.print(i + " ");
}
System.out.println(); // Move to the next line

// Example of a while loop
int count = 0;
System.out.println("Counting from 0 to 4 using a while loop:");
while (count < 5) {
System.out.print(count + " ");
count++;
}
System.out.println(); // Move to the next line

// Example of a do-while loop
int doWhileCount = 0;
System.out.println("Counting from 0 to 4 using a do-while loop:");
do {
System.out.print(doWhileCount + " ");
doWhileCount++;
} while (doWhileCount < 5);
System.out.println(); // Move to the next line

// Example of a foreach loop
int[] numbers = {10, 20, 30, 40, 50};
System.out.println("Printing array elements using a foreach loop:");
for (int num : numbers) {
System.out.print(num + " ");
        }
    }
}
