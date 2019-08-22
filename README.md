# VECode
import java.util.*;
class DatePrint
{
    void main()
    {
        Scanner sc=new Scanner(System.in);
        int n,n1,n2,n3;
        String s,s1,s2,s3;
        System.out.println("Enter the date in six digit format:");
        n=sc.nextInt();
        s=Integer.toString(n);
        s1=s.substring(0,2);
        s2=s.substring(2,4);
        s3=s.substring(4);
        n1=Integer.valueOf(s1);
        n2=Integer.valueOf(s2);
        n3=Integer.valueOf(s3);
        if(n3%4==0)
        {
            if(n2==1)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"January,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==2)
            {
                if(n1>=1&&n1<=29)
                {
                    System.out.println(n1+"th "+"February,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==3)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"March,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==4)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"April,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==5)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"May,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==6)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"June,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==7)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"July,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==8)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"August,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==9)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"September,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==10)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"October,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==11)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"November,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==12)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"December,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else
            {
                System.out.println("INVALID DATE");
            }
        }
        else
        {
            if(n2==1)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"January,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==2)
            {
                if(n1>=1&&n1<=28)
                {
                    System.out.println(n1+"th "+"February,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==3)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"March,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==4)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"April,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==5)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"May,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==6)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"June,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==7)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"July,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==8)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"August,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==9)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"September,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==10)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"October,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==11)
            {
                if(n1>=1&&n1<=30)
                {
                    System.out.println(n1+"th "+"November,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else if(n2==12)
            {
                if(n1>=1&&n1<=31)
                {
                    System.out.println(n1+"th "+"December,"+n3);
                    System.out.println("VALID DATE");
                }
                else
                {
                    System.out.println("INVALID DATE");
                }
            }
            else
            {
                System.out.println("INVALID DATE");
            }
        }
    }
}
