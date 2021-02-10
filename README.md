# timeandminute
import  java.util;
public class pub
{
  public  static void main (string[] args)
  {
    scanner s=new scanner(system.in);
    int a;
    a=s.nextInt();
    int year,days;
    int cn=60*24*365;
    year=a/cn;
    system.out.print(year+" years");
    a=a-(year*cn);
    int cm=60*24;
    days=a/cm;
    system.out.print("and "+days+" days.");
   }
 }
