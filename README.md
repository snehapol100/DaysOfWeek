import java.util.*;
import java.lang.*;
public class DaysOfWeek
{
    public static void main(String [] args)
    {
        int Day=0;
        Scanner Sc=new Scanner(System.in);

        System.out.print("\n Enter Day Number(1-7):");
        Day=Sc.nextInt();

        if( Day <= 0 || Day > 7)
        {
            System.out.print("\n Invalid Day Number");
        }
        else if( Day == 1)
        {
            System.out.print("\n Day is Monday");
        }
        else if( Day == 2)
        {
            System.out.print("\n Day is Tuesday");
        }
        else if( Day == 3)
        {
            System.out.print("\n Day is Wednesday");
        }
        else if( Day == 4)
        {
            System.out.print("\n Day is Thursday");
        }
        else if( Day == 5)
        {
            System.out.print("\n Day is Friday");
        }
        else if( Day == 6)
        {
            System.out.print("\n Day is Saturday");
        }
        else if( Day == 7)
        {
            System.out.print("\n Day is Sunday");
        }
        System.out.print("\n Thanks..!!!");
    }
}
