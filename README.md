class Student { 
    private String name;
    private int rollNumber;
    private double marks;
    public void setName(String name) {
        this.name = name;
    }
    public void setRollNumber(int rollNumber) {
        this.rollNumber = rollNumber;
    }
    public void setMarks(double marks) {
        this.marks = marks;
    }
    public String getName() {
        return name;
    }
    public int getRollNumber() {
        return rollNumber;
    }
    public double getMarks() {
        return marks;
    }
    public void displayDetails() {
        System.out.println("Student Name: " + getName());
        System.out.println("Roll Number: " + getRollNumber());
        System.out.println("Marks: " + getMarks());
    }
}
public class GetterSetterExample {
    public static void main(String[] args) {  
        Student student = new Student();
        student.setName("John Doe");
        student.setRollNumber(101);
        student.setMarks(85.5);
        student.displayDetails();
    }
}
output

Student Name: John Doe
Roll Number: 101
Marks: 85.5
