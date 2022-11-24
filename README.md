# Java-Exception-Handling
import java.util.*;
//Example 1
class HelloWorld {
    public static void main(String[] args) {
       Scanner val = new Scanner(System.in);
       try{
       double a,b;
       System.out.println("enter the numerator \n");
       a=val.nextInt();
       System.out.println("enter the denominator");
       b=val.nextInt();
       System.out.println("division :"+ a/b);
       }
       catch(ArithmeticException e){
           System.out.println(e.getMessage());
       }
       
    }
}
