# sum-of-even-and-numbers-in-array 
import java.util.*;
public class File1
{
public class void main(String[] args)
{
int n,e_sum =0,o_sum =0;
Scanner obj = new Scanner(System.in);
System.out.println("enter array size:");
n= obj.nextInt();
int a[] = new int[n];
for(int i =0; i<n; i++)
{
  a[i] = obj.nextInt();
}
  for(int i=0; i < n; i++)
  {
      if(a[i]%2==1 && i%2==0)
            e_sum = e_sum+a[i];
       else if(a[i]%2==1 && i%2 ==1)
       o_sum = o_sum + a[i];
    }
    System.out.println(e_sum+" "+o_sum);
 }
 }
    
