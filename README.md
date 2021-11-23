# homework4
// Name: Main.java 
package com.company;

public class Main {
    public static void main(String[] args) {
        Train train1 = new Train("electric", "oval", 45.5F, 12, "green");
        Train train2 = new Train("petrol", "rectangle", 30.5F, 10, "white");

        Way way1 = new Way("Nekrasovka-Kosino", 1000);
        Way way2 = new Way ("Kosino-Nekrasovka", 1000);

        Priceway priceway = new Priceway (45, 65);

        Tunnel tunnel1 = new Tunnel(200);
        Tunnel tunnel2 = new Tunnel(300);
        Tunnel tunnel3 = new Tunnel(500);

        Depo depo = new Depo(15, "Lermontovsy prospekt");
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

      public Train(String type, String form, float wagonssquare, int wagons, String color){
            this.type = type;
            this.form = form;
            this.wagonssquare = wagonssquare;
            this.wagons = wagons;
            this.color = color;



      }
            }



// Name: Way.java
package com.company;

public class Way {
    String name;
    int distance;
    public Way(String name, int distance) {
       this.name = name;
       this.distance = distance;
    }
}



// Name: Priceway.java
package com.company;

public class Priceway{

    int morningprice;
    int nightprice;

    public Priceway(int morgenprice, int nighprice){
    this.morningprice = morningprice;
    this.nightprice = nightprice;
    }
}




// Name: Tunnel.java
package com.company;

public class Tunnel{

    int length;

    public Tunnel(int length) {
        this.length = length;
    }

    }




// Name: Depo.java
package com.company;

public class Depo {
    int parkingplace;
    String located;
    public Depo(int parkingplace, String located){
        this.parkingplace = parkingplace;
        this.located = located;

    }

}
