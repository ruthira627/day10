class Account {
    private double balance;

    Account(double balance) {
        this.balance = balance;
    }

    double getBalance() {
        return balance;
    }

    void calculateInterest() {}
}

class SavingsAccount extends Account {
    SavingsAccount(double balance) {
        super(balance);
    }

    void calculateInterest() {
        System.out.println("Savings Interest = " +
                (getBalance() * 0.05));
    }
}

class CurrentAccount extends Account {
    CurrentAccount(double balance) {
        super(balance);
    }

    void calculateInterest() {
        System.out.println("Current Interest = " +
                (getBalance() * 0.02));
    }
}

public class Main {
    public static void main(String[] args) {
        Account a1 = new SavingsAccount(10000);
        Account a2 = new CurrentAccount(10000);

        a1.calculateInterest();
        a2.calculateInterest();
    }
}
