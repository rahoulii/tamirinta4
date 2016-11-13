# tamirinta4

import java.util.*;

public class tamirinta4 {

    public static void inputBirthday() {
        int number = 0, number2 = 0;
        String sentence = "";
        Scanner console = new Scanner(System.in);
        System.out.println("On what day of the month were you born?");
        number = console.nextInt();
        System.out.println("What is the name of the month in which you were born?");
        sentence = console.next();
        System.out.println("During what year where you born?");
        number2 = console.nextInt();
    }

    public static void main(String[] args, String number, String sentence, String number2) {
        inputBirthday();
        System.out.print("You were born on" + sentence + number
                + "," + number2 + ". You're might old!");
    }
}
