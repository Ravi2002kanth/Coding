import java.util.*;
public class Solution{
    public static void main(String[] args){
        Scanner s=new Scanner(System.in);
        char Name=s.next().charAt(0);
        int Mark_1=s.nextInt();
        int Mark_2=s.nextInt();
        int Mark_3=s.nextInt();
        // System.out.println(Mark_1 +" " +Mark_2 +" "+Mark_3); 
        int avg=0;
        avg=(Mark_1+Mark_2+Mark_3)/3;
        System.out.println(Name);
        System.out.println(avg);
    }
}
