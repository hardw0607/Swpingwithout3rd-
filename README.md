# Swpingwithout3rd-
Swpingwithout3rd 
package mypackages;

public class Swpingwithout3rd {
    public static void swap(int a , int b){
        a = a + b;
        b = a - b;
        a = a - b;

        System.out.println("Inside swapping");
        System.out.println("a = " + a);
        System.out.println("b = " + b);

        
    }
    public static void main(String[] args) {
        int x = 4 ;
        int y = 6;
        
        System.out.println("Before swapping");
        System.out.println(" x = " + x);
        System.out.println(" y = " + y);


        swap(x , y);

        System.out.println("After Swapping function ");
        System.out.println(" x = " + x);
        System.out.println(" y = " + y);
    }
    
}
//output
Inside swapping
a = 6
b = 4
After Swapping function
 x = 4
 y = 6
