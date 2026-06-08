class FoodItem {
    private String name;

    FoodItem(String name) {
        this.name = name;
    }

    public String getName() {
        return name;
    }

    void generateBill() {}
}

class Pizza extends FoodItem {
    Pizza(String name) {
        super(name);
    }

    void generateBill() {
        System.out.println(getName() + " Bill = Rs.250");
    }
}

class Burger extends FoodItem {
    Burger(String name) {
        super(name);
    }

    void generateBill() {
        System.out.println(getName() + " Bill = Rs.150");
    }
}

class Dessert extends FoodItem {
    Dessert(String name) {
        super(name);
    }

    void generateBill() {
        System.out.println(getName() + " Bill = Rs.100");
    }
}

public class Main {
    public static void main(String[] args) {
        FoodItem f1 = new Pizza("Cheese Pizza");
        FoodItem f2 = new Burger("Veg Burger");
        FoodItem f3 = new Dessert("Ice Cream");

        f1.generateBill();
        f2.generateBill();
        f3.generateBill();
    }
}
