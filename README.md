
package Learnprogramming;

import java.io.IOException;

public class Main {

    public static void main(String[] args) {

        Runtime rs = Runtime.getRuntime();
        try {


            rs.exec("notepad");
        } catch (IOException e) {

            System.out.println(e);


        }

    }
}

