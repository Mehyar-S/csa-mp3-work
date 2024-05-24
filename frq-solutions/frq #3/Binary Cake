import java.util.*;

public class Main {
  public static void main(String[] args) {
    Scanner s = new Scanner (System.in);
    System.out.print("Enter your age: ");
    int age = s.nextInt();
    System.out.println();
    binaryCake(age);
    s.close();
  }
  
  public static void binaryCake(int age) {
    int[] cake = {0,0,0,0,0,0,0};
    for (int i=0; i<7; i++) {
      if (age >= Math.pow(2,6-i)) {
        cake[i]=1;
        age -= Math.pow(2,6-i);
      }
    }
      
    for (int i:cake) {
      if (i==1) System.out.print("🔥 ");
      else System.out.print("⬛️ ");
    }
    System.out.println();

    for (int j=0; j<2; j++) {
      for (int i:cake) {System.out.print("🟥 ");}
      System.out.println();
    }

    for (int j=0; j<5; j++) {
      for (int i=0; i<10; i++) {System.out.print("⬜");}
      System.out.println();
    }

    System.out.print("\nHAPPY BIRTHDAY!!!!");
  }
}
