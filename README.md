# BiggestNumber
find biggest number
mport  java.util.Scanner;
public class BiggestofthreeNumbers
{
  public static void main(String [] args)
 {
  int num1,num2,num3;
  Scanner sc=new Scanner(System.in);
  System.out.println("Enter the 1st number:");
  num1=sc.nextInt();
  System.out.println("Enter the 2nd number:");
  num2=sc.nextInt();
  System.out.println( "Enter the 3rd number:");
  num3=sc.nextInt();
  if(num1>num2&&num1>num3)
  {
   System.out.println("Biggest number is"+num1);
  }
  else if(num2>num3)
  {
  System.out.println("Biggest number is"+num2);
  }
  else
  {
  System.out.println("Biggest number is"+num3);
  }
}
} 
