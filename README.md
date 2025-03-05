package week4.java;


import java.util.Scanner;

public class JavaPrac {
	//for retirement task 
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("What is your current age ");
        int currentAge = scanner.nextInt();

        System.out.print("At what age would you like to retire? ");
        int retirementAge = scanner.nextInt();

          int yearsLeft = retirementAge - currentAge;
          
       
         int currenttYear = java.util.Calendar.getInstance().get(java.util.Calendar.YEAR);// cleander
        
         int retirementYear = currenttYear + yearsLeft;

       
        
        if (yearsLeft < 0) {
            System.out.println("You can already retire!!! ");
        } else {
            System.out.println("You have " + yearsLeft + " years left until you can retire");
            System.out.println("It's :  " + currenttYear + ", so you can retire in : " + retirementYear + " ");
        }
  
}
}


-----------------------------------------------------------------------------------------


package week4.java;


import java.util.Scanner;

public class JavaPrac {
	//for  Calculate the area of ​​a rectangular room
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
           System.out.print("ما هو طول الغرفة بالمتر؟ ");
           
        double length = scanner.nextDouble();

        System.out.print("ما هو عرض الغرفة بالمتر؟ ");
        double width = scanner.nextDouble();

        double areaInMeters = length * width;
        
        double areaInFeet = areaInMeters * 10.7639;

        System.out.println(" أدخلت أبعاد  " + length + "بعرض  " + width  );
        System.out.println("المساحة :");
        System.out.println(areaInMeters + " متر مربع");
        System.out.println(areaInFeet + " قدم مربع");
    }
}
