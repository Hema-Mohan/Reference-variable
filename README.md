# Reference-variable
class Student {
    int id;
    String name;
}

Class TestStudent {
    Public static void main(String[] args) {
        Student s1 = new Student();
        Student s2 = new Student();

        s1.id = 101;
        s1.name = "Sonoo";

        s2.id = 102;
        s2.name = "Amit";

        System.out.println("Student 1: " + s1.name);
        System.out.println("Student 2: " + s2.name);
    }
}

OUTPUT:

Student 1: Sonoo
Student 2: Amit
