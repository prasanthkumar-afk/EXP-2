import java.util.*;
class ArmStrong
{
  public static void main(String args [])
  {
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter a no: ");
     int n=sc.nextInt();
     int r,sum=0,d=n;
     while(n>0)
      {
        r=n%10;
        sum=sum+(r*r*r);
        n=n/10;
      }
      if(d==sum)
      System.out.println("It is Armstrong number");
      else
      System.out.println("Not an Armstrong number");
     }
 }