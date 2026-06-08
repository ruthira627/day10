class Product {
    void applyDiscount(double price) {}
}

class Electronics extends Product {
    void applyDiscount(double price) {
        System.out.println("Electronics Price = " + (price * 0.90));
    }
}

class Clothing extends Product {
    void applyDiscount(double price) {
        System.out.println("Clothing Price = " + (price * 0.80));
    }
}

class Grocery extends Product {
    void applyDiscount(double price) {
        System.out.println("Grocery Price = " + (price * 0.95));
    }
}

public class Main {
    public static void main(String[] args) {
        Product p1 = new Electronics();
        Product p2 = new Clothing();
        Product p3 = new Grocery();

        p1.applyDiscount(1000);
        p2.applyDiscount(1000);
        p3.applyDiscount(1000);
    }
}
