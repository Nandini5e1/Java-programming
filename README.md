# Java-programming
import java.io.*;
import java.util.*;

class RandomEx{

      public static void main(String args[]){

            int d=0;

            for(int i=0;i<=10000;i++){

                
                int d1=(int)(Math.random()*6)+1;
                int d2=(int)(Math.random()*6)+1;
                if(d1==d2)
                  d++;
                
            }
            System.out.println("The two dice have same number  "+d+" times");
      }

}
