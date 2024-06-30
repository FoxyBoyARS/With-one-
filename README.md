
// рекурсивная реализация Factorial
import java.util.Scanner;
class RecursiveFactorial
{
 public static void main(String[] args)
 {
  Scanner input=new Scanner(System.in);
  System.out.print("Find the Factorial of: ");
  int num=input.nextInt();
  System.out.println("Factorial of "+num+" = "+fact(num));
 }
static long fact(int n)
 {
  if(n < 2) return 1;
  return n * fact(n-1);
 }
}
// End
