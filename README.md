# ClassTest
//*ClassTest shows you how to create a class within a class and how to call methods in java.*//
//*@00coder*//
import java.util.Scanner;
public class ClassTest {
      public static void main(String[] args) {
          Scanner in = new Scanner(System.in); 
          Class class1 = new Class(); //Here we create the object of our class called class1//
          System.out.println("Enter your class's name:"); 
          String name=in.nextLine();
          class1.showMessage(name); //Here we call the method from the other class
    }
}
public class Class {
    public void showMessage(String className) { //Here we build the method that has one parameter 
        System.out.println("Welcome to "+className);
    }
}
