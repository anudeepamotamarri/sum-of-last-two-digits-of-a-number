# sum-of-last-two-digits-of-a-number 
import java.util.Scanner;
public class Main{
public static void main(String[] args){
Scanner num=new Scanner (System.in);
int n=num.nextInt();
int sum=0;
sum=sum+(n%10)+((n%100)/10);
System.out.println(sum);
}
}
