import java.util.*;
public static void main(String[] args) {
    Map<String. Double> students = new HashMap<>();
        students.put("Alice", 1.1);
        students.put("Bob", 3.1);
        students.put("Charlie", 2.2);
        students.put("Diana", 2.9);

        double maxGpa = Collections. max(students.values());

        System.out.println("Highest GPA: " + maxGpa);
        System.out.println("Students with the highest GPA:");
        for (Map.Entry<String. Double> entry : students.entrySet()) {
            if (entry.getValue() == maxGpa) {
                System.out.println("- " + entry.getKey());
            }
        }
        System.out.println();
        double sum= 0;
        for (double gpa : students.values()) {
            sum += gpa;
    }
        double averageGpa = sum / students.size();
        System.out.println("Average GPA: " + averageGpa);
    }
    int belowAverageCount = 0;
    for(double gpa: students.values()) {
        if (gpa < averageGpa) {
            belowAverageCount++;
        }
    }
    System.out.println("Number of students below average GPA: " + belowAverageCount);
}