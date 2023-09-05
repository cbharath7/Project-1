import java.util.*;

public class CollectionExample {
    public static void main(String[] args) {
       
        Set<String> set = new HashSet<>();

        
        set.add("Apple");
        set.add("Banana");
        set.add("Orange");
        set.add("Mango");

        
        System.out.println("Set Elements: " + set);

       
        List<Integer> list = new ArrayList<>();

       
        list.add(10);
        list.add(20);
        list.add(30);
        list.add(40);

        
        System.out.println("List Elements: " + list);

        
        Map<String, Integer> map = new HashMap<>();

        
        map.put("John", 25);
        map.put("Alice", 30);
        map.put("Bob", 22);
        map.put("Eve", 28);

        
        System.out.println("Map Elements: " + map);

        
        String name = "Alice";
        if (map.containsKey(name)) {
            int age = map.get(name);
            System.out.println(name + "'s age is " + age + " years.");
        } else {
            System.out.println(name + " not found in the map.");
        }
    }
}
