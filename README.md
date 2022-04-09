# poovarasan0
import java.util.*;
public class Main
{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner(System.in);
        int num=sc.nextInt();
        int bin=0;
        int m=1;
        while(num>0)
        {
            bin=bin+(num%8)*m;
            m=m*10;
            num=num/8;
        }
        System.out.println(bin);
    }
}
