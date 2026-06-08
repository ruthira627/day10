class Book {
    private String title;

    Book(String title) {
        this.title = title;
    }

    public String getTitle() {
        return title;
    }

    void borrowBook() {
        System.out.println("Borrowing Rules");
    }
}

class PrintedBook extends Book {
    PrintedBook(String title) {
        super(title);
    }

    @Override
    void borrowBook() {
        System.out.println(getTitle() + " : Return within 15 days");
    }
}

class EBook extends Book {
    EBook(String title) {
        super(title);
    }

    @Override
    void borrowBook() {
        System.out.println(getTitle() + " : Access valid for 30 days");
    }
}

public class Main {
    public static void main(String[] args) {
        Book b1 = new PrintedBook("Java");
        Book b2 = new EBook("Python");

        b1.borrowBook();
        b2.borrowBook();
    }
}
