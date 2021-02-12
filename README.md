# Assignment3

import java.util.Scanner;
public class Hw3pt1 {
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
	System.out.println("Give me a number.");
	int x=in.nextInt();
	if(x<0){
	    System.out.println(x+" is a negative number");
	   }
	   else{
	       System.out.println(x+" is a positive number");
	   }
   }
}

import java.util.Scanner;
public class Hw3pt2 {
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        int x,z,y;
        System.out.println("Give me 3 numbers");
        System.out.println("Number one.");
        x=in.nextInt();
        System.out.println("Number two.");
        z=in.nextInt();
        System.out.println("Number three.");
        y=in.nextInt();
         if( x >= z && x >= y){
          System.out.println(x+" is the largest Number");
        }
      else if (z >= x && z >= y){
          System.out.println(z+" is the largest Number");
        }
      else{
          System.out.println(y+" is the largest Number");
        }
    }
}



import java.util.Scanner;
public class Hw3pt3 {
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        int x;
        System.out.println("Give me a number from 1 to 7");
        x=in.nextInt();
        System.out.println(getDayName(x));
    }
    public static String getDayName(int x) {
        String dayName = "";
        switch (x) {
            case 1: dayName = "Monday"; break;
            case 2: dayName = "Tuesday"; break;
            case 3: dayName = "Wednesday"; break;
            case 4: dayName = "Thursday"; break;
            case 5: dayName = "Friday"; break;
            case 6: dayName = "Saturday"; break;
            case 7: dayName = "Sunday"; break;
            default:dayName = "Invalid day range";
        }
        return dayName;
    }
}

