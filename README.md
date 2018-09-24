# JAVA2018
import java.util.Scanner;
  public class Main {

        public static void main(String[] args) {
            System.out.print("What is your number?");
            Scanner in = new Scanner (System.in);
            int number = in.nextInt();
            boolean prime=true;
            int i=2;
            int remainder;
            int divisible;
            remainder=number % i;
            if(remainder==0) {
                prime = false;
                divisible = i;
                System.out.println(number + " is divisible by " + divisible);
            }
            i++;

        if (prime)
                System.out.println(number+" is a prime number! :)");
            else
                    System.out.println(number + " is not a prime number :(");
    }
}
