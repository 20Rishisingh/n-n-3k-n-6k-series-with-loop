/*      You are required to write a program that takes two integer inputs: n and k. The program should generate a series of numbers based on the following pattern:

  n, n-3k, n-6k, n-9k, n-12k, and so on, until the value to be printed is greater than zero.

Your task is to implement a program that will output this series of number.
 
 "Sample Input"                 "Sample Output"
  20                              20 17 14 11 8 5 2 
  1      
*/



import java.io.*;
import java.util.*;

public class Main {
    public static void main(String[] args) {
  Scanner asd = new Scanner (System.in);
    int n = asd.nextInt();
    int k = asd.nextInt();

        for (int i=0;i<=n;i+=3){
           int A = n-(i*k);
                if (A > 0)
                System.out.print(A+" ");
        }            
    }
}
