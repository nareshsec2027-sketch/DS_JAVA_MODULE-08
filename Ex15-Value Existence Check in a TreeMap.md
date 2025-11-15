## Ex15 Value Existence Check in a TreeMap

## AIM:

To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm

Create a TreeMap with key–value pairs.

Use containsValue() to check if the value exists.

Display the result.

## Program:
```
Program to check whether a given value exists in a TreeMap.
Developed by: Naresh P.S.
RegisterNumber: 212223040127
Date: 11-11-2025

import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {
        TreeMap<Integer, String> map = new TreeMap<>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");

        String value = "Banana";

        if (map.containsValue(value))
            System.out.println(value + " exists in the TreeMap.");
        else
            System.out.println(value + " does NOT exist in the TreeMap.");
    }
}
```

## Output:
Banana exists in the TreeMap.

## Result:

Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
