class Payment {
    protected double amount;

    Payment(double amount) {
        this.amount = amount;
    }

    void processPayment() {}
}

class CreditCardPayment extends Payment {
    CreditCardPayment(double amount) {
        super(amount);
    }

    void processPayment() {
        System.out.println("Credit Card Payment: Rs." + amount);
    }
}

class UpiPayment extends Payment {
    UpiPayment(double amount) {
        super(amount);
    }

    void processPayment() {
        System.out.println("UPI Payment: Rs." + amount);
    }
}

class NetBankingPayment extends Payment {
    NetBankingPayment(double amount) {
        super(amount);
    }

    void processPayment() {
        System.out.println("Net Banking Payment: Rs." + amount);
    }
}

public class Main {
    public static void main(String[] args) {
        Payment p1 = new CreditCardPayment(5000);
        Payment p2 = new UpiPayment(2000);
        Payment p3 = new NetBankingPayment(3000);

        p1.processPayment();
        p2.processPayment();
        p3.processPayment();
    }
}
