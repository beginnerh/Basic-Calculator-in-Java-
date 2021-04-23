# Basic-Calculator-in-Java-package calculator;

import java.util.Scanner;

public class calculator {

  public static void main(String[] args) {

  Scanner scan = new Scanner (System.in);

  

  int number1;

  int number2;

  int number3;

  int number4;

  int number5;

  int number6;

  int number7;

  int number8;

  

  int Sum;

  int Difference;

  int Product;

  int Quotient;

  

  // SUM 

  System.out.println("Sum:");

  number1 = scan.nextInt();

  

  System.out.print("+");

  number2 = scan.nextInt();

  

  Sum = number1 + number2;

  System.out.println("Sum is:" + Sum);

  

  // DIFFERENCE

  

  System.out.println("difference:");

  number3 = scan.nextInt();

  

  System.out.print("-");

  number4 = scan.nextInt();

  

  Difference = number3 - number4;

  System.out.println("Difference is:" + Difference);

  

  

  // PRODUCT

  System.out.println("Product:");

  number5 = scan.nextInt();

  

  System.out.print("*");

  number6 = scan.nextInt();

  

  Product = number5 * number6;

  System.out.println("Product is:" + Product);

  

  // Quotient

  

  System.out.println("Quotient:");

  number7 = scan.nextInt();

  

  System.out.print("/");

  number8 = scan.nextInt();

  

  Quotient = number7 / number8;

  System.out.println("Quotient is:" + Quotient);

  

  scan.close();

  

  

 

  

  

   

  }

}
