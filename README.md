Remove brackets from an algebraic expression
In this program, we’re going to remove brackets from an algebraic expression. Take a String input from the user and store it in the variable called “s”. After that use replaceAll() method which was present in string class the work of replaceAll() method is to replace some old thing with some new thing so here we’re using a regular expression to replace brackets with white spaces from an algebraic expression like s.replaceAll(“[(){}]”,””) and after that simply print new expression which doesn’t have any brackets.

Java program to remove brackets from an algebraic expression
Algorithm
First take String input from user and Store it in the variable called as “s”.
After that use replaceAll() method .
Use regular expression to replace brackets present in algebraic expression with whitespaces.
Atlast simply print that expression after removing brackets.
Code in Java
Run
import java.util.Scanner;

public class Main {

public static void main(String[] args) {
     
     String s = "(a+b)=c";
     String result = s.replaceAll("[(){}]","");
     System.out.println("Expression without brackets : "+result);
  }
}
Output
Expression without brackets : a+b=c
