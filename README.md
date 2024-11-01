public class Student {
    private String name;
    private String course;
    private String university;
    public Student(String name, String course, String university) {
        this.name = name;
        this.course = course;
        this.university = university;
    }
    public void displayInfo() {
        System.out.println("Name: " + name);
        System.out.println("Course: " + course);
        System.out.println("University: " + university);
    }
    public static void main(String[] args) {
        Student student = new Student("Sagardip Debnath", "B.Tech in Computer Science", "VIT Bhopal University");
        student.displayInfo();
    }
}


