import java.util.*;

public class Main {
    public static void main(String[] args) {
        // Set Example
        Set<String> fruitSet = new HashSet<>();
        fruitSet.add("Grape");
        fruitSet.add("Kiwi");
        fruitSet.add("Strawberry");
        fruitSet.add("Kiwi");

        System.out.println("Set Example:");
        for (String fruit : fruitSet) {
            System.out.println(fruit);
        }
        System.out.println();

        // List Example
        List<Integer> numberList = new ArrayList<>();
        numberList.add(1);
        numberList.add(2);
        numberList.add(3);
        numberList.add(4);

        System.out.println("List Example:");
        for (int number : numberList) {
            System.out.println(number);
        }
        System.out.println();

        // Map Example
        Map<String, Integer> studentScores = new HashMap<>();
        studentScores.put("Roshan", 1);
        studentScores.put("Varun", 4);
        studentScores.put("Ajith", 7);
        studentScores.put("Sandeep", 5);

        System.out.println("Map Example:");
        for (Map.Entry<String, Integer> entry : studentScores.entrySet()) {
            System.out.println(entry.getKey() + ": " + entry.getValue());
        }
    }
}
