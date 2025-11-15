## Ex11: Convert HashSet to ArrayList in Java

## DATE:15-11-25
## AIM: To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.

## Algorithm

Create a HashSet and insert distinct integers.

Convert the HashSet into an ArrayList.

Display the ArrayList elements.

## Program
```
Program to convert a collection of distinct integers stored in a HashSet
into an ArrayList and display its contents.
Developed by: Naresh P.S.
RegisterNumber: 212223040127


import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(10);
        set.add(20);
        set.add(30);

        ArrayList<Integer> list = new ArrayList<>(set);

        System.out.println("ArrayList elements: " + list);
    }
}
```
## Output
ArrayList elements: [10, 20, 30]

## Result

The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList.
