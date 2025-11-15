## Ex11 Convert HashSet to ArrayList in Java

## AIM:

To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.

## Algorithm

Create a HashSet and insert elements.

Create an ArrayList.

Add all elements from the HashSet to ArrayList.

Display the ArrayList.

## Program:
```
Program to convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
Developed by: Naresh P.S.
RegisterNumber: 212223040127
Date: 11-11-2025


import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(10);
        set.add(30);
        set.add(20);
        set.add(40);

        ArrayList<Integer> list = new ArrayList<>(set);

        System.out.println("ArrayList elements: " + list);
    }
}
```

## Output:
ArrayList elements: [20, 40, 10, 30]

## Result:

The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList.
