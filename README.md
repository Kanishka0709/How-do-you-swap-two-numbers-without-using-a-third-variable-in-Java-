import java.util.*;
public class Main{ 
  public static void main(String[] args){
  int a=35;
    int b=45;
    System.out.println("Numbers before swapping are "+a+" and "+b);
    //Let's say a=20 and b=40
    a=a+b; //a=60(20+40)
    b=a-b; //b=20(60-40)
    a=a-b; //a=40(60-20)
    System.out.println("Numbers after swapping are "+a+" and "+b);
}
}

//For user input
import java.util.*;
public class Main{
  public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int a=sc.nextInt();
      int b=sc.nextInt();
    System.out.println("Numbers before swapping are "+a+" and "+b);
    //Let's say a=20 and b=40
    a=a+b; //a=60(20+40)
    b=a-b; //b=20(60-40)
    a=a-b; //a=40(60-20)
    System.out.println("Numbers after swapping are "+a+" and "+b);
}
}
