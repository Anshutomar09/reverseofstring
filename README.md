# reverseofstring

//print reverse of a string
import java.util.*;
public class HelloWorld{
     public static void printrev(String str , int idx){
         if(idx==0){
            System.out.println(str.charAt(idx));   
         }
         System.out.print(str.charAt(idx));
         printrev(str, idx-1);
     }
     public static void main(String []args){
       String str = "anshu";
       printrev(str , str.length()-1);
     }
}
