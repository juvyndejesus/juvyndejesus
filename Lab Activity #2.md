package javaapplication5;

import java.util.Scanner;


public class JavaApplication5 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
      Scanner scan = new Scanner(System.in);
        System.out.print("Please enter the shape:");
        String input = scan.next();
        
       if ("RECTANGLE".equalsIgnoreCase(input)) {
           System.out.print("Enter the length of RECTANGLE: ");
           double W = scan.nextDouble();
           System.out.println("Enter the width of RECTANGLE: ");
           double L = scan.nextDouble();
           
           double P = 2 * (L + W);
           double A = L * W;
           System.out.println("The area of the RECTANGLE is: " + A);
           System.out.println("The area of RECTANGLE is: " + P);
       } else {
       }
        if ("CIRCLE".equalsIgnoreCase(input)) {
            System.out.print("Enter the radius: ");
            
            double radius = scan.nextDouble();
            double circumference = Math.PI * 2 * radius;
            System.out.println("The circumference of the CIRCLE is: " + circumference);
            double area = Math.PI * (radius); 
            System.out.println("The area of CIRCLE is: " + area);
            
    }  
        if (!"CYLINDER".equalsIgnoreCase(input)) {
        } else {
            ;
        }
{
        System.out.print("Enter the radius of the CYLINDER: ");
        double radiusCylinder = scan.nextDouble();
        double radiusCylinder_Squared = radiusCylinder * radiusCylinder;
        
        System.out.print("Enter the height of the CYLINDER: ");
          var heightCylinder = scan.nextDouble();
        
          var v = Math.PI * radiusCylinder_Squared * heightCylinder;
          var a = (radiusCylinder *2 * Math.PI * heightCylinder + 2 * Math.PI *radiusCylinder_Squared);
        System.out.println("The surface area of the CYLINDER is : " + a);
        System.out.println("The volume of the CYLINDER is: " + v);
        
        }
        
    } 
    }
