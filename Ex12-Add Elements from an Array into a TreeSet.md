Ex12 Add Elements from an Array into a TreeSet
DATE:

11-11-2025

AIM:

To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.

Algorithm

Create an integer array.

Create a TreeSet.

Add array elements to the TreeSet.

Display the TreeSet (sorted automatically).

Program:
/*
Program that adds elements from an array into a TreeSet and displays the elements in sorted order.
Developed by: Naresh P.S.
RegisterNumber: 212223040127
Date: 11-11-2025
*/

import java.util.*;

public class ArrayToTreeSet {
    public static void main(String[] args) {
        int[] arr = {40, 10, 50, 20, 30};

        TreeSet<Integer> set = new TreeSet<>();
        for (int num : arr) {
            set.add(num);
        }

        System.out.println("TreeSet elements in sorted order: " + set);
    }
}

Output:
TreeSet elements in sorted order: [10, 20, 30, 40, 50]

Result:

The program successfully adds elements from an array into a TreeSet.
