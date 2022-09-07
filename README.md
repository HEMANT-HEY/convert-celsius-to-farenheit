# convert-celsius-to-farenheit 
//convert temparature celcius to farenheit.

 java.util.Scanner;

class HelloWorld {

    public static void main(String[] args) {

      Scanner sc= new Scanner (System.in);

      System.out.println("enter the tempt.");

       float ct= sc.nextFloat();

      System.out.println("Enter the celcius tempt.:"+ct);

   float Frnttempt=((9*ct+160)/5);

       

      System.out.println("the feranheit tempt is :"+Frnttempt);

    }

}
