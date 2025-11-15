## Ex13 Fill the First 10 Elements of an Array with a Constant using Arrays.fill()

## AIM:

To write a Java program that fills the first 10 elements of an array with a constant value using the Arrays.fill() method.

## Algorithm

Create an integer array.

Use Arrays.fill() to assign value 5 to the first 10 positions.

Display the array.

## Program:
```
Program to fill the first 10 elements of an array with a constant value using the Arrays.fill() method.
Developed by: Naresh P.S.
RegisterNumber: 212223040127
Date: 11-11-2025

import java.util.Arrays;

public class FillArray {
    public static void main(String[] args) {
        int[] arr = new int[15];

        Arrays.fill(arr, 0, 10, 5);

        System.out.println("Array after filling first 10 elements: " + Arrays.toString(arr));
    }
}
```
## Output:
Array after filling first 10 elements: [5, 5, 5, 5, 5, 5, 5, 5, 5, 5, 0, 0, 0, 0, 0]

## Result:

The program successfully fills the first 10 elements of the array with the constant value 5 using Arrays.fill().
