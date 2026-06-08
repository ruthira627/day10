class Ride {
    void calculateFare(double distance) {}
}

class BikeRide extends Ride {
    void calculateFare(double distance) {
        System.out.println("Bike Fare = Rs." + (distance * 10));
    }
}

class AutoRide extends Ride {
    void calculateFare(double distance) {
        System.out.println("Auto Fare = Rs." + (distance * 15));
    }
}

class CabRide extends Ride {
    void calculateFare(double distance) {
        System.out.println("Cab Fare = Rs." + (distance * 20));
    }
}

public class Main {
    public static void main(String[] args) {
        Ride r1 = new BikeRide();
        Ride r2 = new AutoRide();
        Ride r3 = new CabRide();

        r1.calculateFare(10);
        r2.calculateFare(10);
        r3.calculateFare(10);
    }
}
