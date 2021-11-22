# homework4
// Name: Main.java 

package com.company;

public class Main {
    public static void main(String[] args) {
        Train train1 = new Train("electric", "oval", 45.5F, 12, "green");
        Train train2 = new Train("petrol", "rectangle", 30.5F, 10, "white");


    }

}
// Name: Train.java

package com.company;

public class Train {

      String type;
      String form;
      float wagonssquare;
      int wagons;
      String color;

      public Train(String type, String form, float wagonssquare, int wagons, String color) {
            this.type = type;
            this.form = form;
            this.wagonssquare = wagonssquare;
            this.wagons = wagons;
            this.color = color;


      }

      public void rides() {
            System.out.println("Едет");
      }

}
