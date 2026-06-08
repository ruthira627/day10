class Course {
    private String courseName;

    Course(String courseName) {
        this.courseName = courseName;
    }

    String getCourseName() {
        return courseName;
    }

    void showBenefits() {}
}

class LiveCourse extends Course {
    LiveCourse(String courseName) {
        super(courseName);
    }

    void showBenefits() {
        System.out.println(getCourseName() + " : Live Interaction");
    }
}

class RecordedCourse extends Course {
    RecordedCourse(String courseName) {
        super(courseName);
    }

    void showBenefits() {
        System.out.println(getCourseName() + " : Learn Anytime");
    }
}

class CertificationCourse extends Course {
    CertificationCourse(String courseName) {
        super(courseName);
    }

    void showBenefits() {
        System.out.println(getCourseName() + " : Certificate Provided");
    }
}

public class Main {
    public static void main(String[] args) {
        Course c1 = new LiveCourse("Java");
        Course c2 = new RecordedCourse("Python");
        Course c3 = new CertificationCourse("AI");

        c1.showBenefits();
        c2.showBenefits();
        c3.showBenefits();
    }
}
