# java-fundamentals
My first Java project to practice GitHub.  A simple Hello World program written in Java.  Learning Java basics with this starter project.
public class HelloJava {
    public static void main(String[] args) {
        System.out.println("Hello, GitHub! This is my first Java program.");
    }
}
import java.util.Scanner;

public class Greeting {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.println("Hello, " + name + "! Welcome to Java on GitHub.");

        sc.close();
    }
}
