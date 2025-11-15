## Ex14 Tracking the First Unique Number in a Stream using LinkedHashMap

## AIM:

To implement a program that tracks the first unique (non-repeating) number in a stream of integers using a LinkedHashMap.

## Algorithm

Create a LinkedHashMap to store numbers and their counts.

For each number in the stream, update its count.

Traverse the map to find the first entry with count = 1.

Display it as the first unique number.

## Program:
```
Program that tracks the first unique (non-repeating) number in a stream of integers using a LinkedHashMap.
Developed by: Naresh P.S.
RegisterNumber: 212223040127
Date: 11-11-2025


import java.util.*;

public class FirstUniqueTracker {
    public static void main(String[] args) {
        int[] stream = {4, 5, 1, 2, 1, 4, 3};

        LinkedHashMap<Integer, Integer> map = new LinkedHashMap<>();

        for (int num : stream) {
            map.put(num, map.getOrDefault(num, 0) + 1);

            System.out.print("After " + num + " → First Unique: ");
            boolean found = false;

            for (Map.Entry<Integer, Integer> entry : map.entrySet()) {
                if (entry.getValue() == 1) {
                    System.out.println(entry.getKey());
                    found = true;
                    break;
                }
            }

            if (!found) System.out.println("None");
        }
    }
}
```

## Output:
After 4 → First Unique: 4
After 5 → First Unique: 4
After 1 → First Unique: 4
After 2 → First Unique: 4
After 1 → First Unique: 4
After 4 → First Unique: 5
After 3 → First Unique: 5

## Result:

The program successfully tracks and returns the first unique number in the stream using a LinkedHashMap.
