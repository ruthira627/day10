class Employee {
    private String name;

    Employee(String name) {
        this.name = name;
    }

    String getName() {
        return name;
    }

    void calculateSalary() {}
}

class FullTimeEmployee extends Employee {
    FullTimeEmployee(String name) {
        super(name);
    }

    void calculateSalary() {
        System.out.println(getName() + " Salary = Rs.50000");
    }
}

class PartTimeEmployee extends Employee {
    PartTimeEmployee(String name) {
        super(name);
    }

    void calculateSalary() {
        System.out.println(getName() + " Salary = Rs.20000");
    }
}

class Intern extends Employee {
    Intern(String name) {
        super(name);
    }

    void calculateSalary() {
        System.out.println(getName() + " Stipend = Rs.10000");
    }
}

public class Main {
    public static void main(String[] args) {
        Employee e1 = new FullTimeEmployee("Arun");
        Employee e2 = new PartTimeEmployee("Kavi");
        Employee e3 = new Intern("Ravi");

        e1.calculateSalary();
        e2.calculateSalary();
        e3.calculateSalary();
    }
}
