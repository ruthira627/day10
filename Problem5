class Patient {
    private String name;

    Patient(String name) {
        this.name = name;
    }

    String getName() {
        return name;
    }

    void calculateBill() {}
}

class InPatient extends Patient {
    InPatient(String name) {
        super(name);
    }

    void calculateBill() {
        System.out.println(getName() + " Bill = Rs.10000");
    }
}

class OutPatient extends Patient {
    OutPatient(String name) {
        super(name);
    }

    void calculateBill() {
        System.out.println(getName() + " Bill = Rs.500");
    }
}

public class Main {
    public static void main(String[] args) {
        Patient p1 = new InPatient("Ram");
        Patient p2 = new OutPatient("Sam");

        p1.calculateBill();
        p2.calculateBill();
    }
}
