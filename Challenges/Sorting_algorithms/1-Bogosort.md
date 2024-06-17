# Bogo sort

Best way to start learning sorting is to start with the simplest algorithm and move towards more challenging ones.

Bogosort is a famous sorting algorithm that is used mostly for educational purposes.
The algorithm is famously bad for commercial use as it is fully based on shuffling the array.

Create a function that sorts an array by shuffling it untill it is in order. Built in array related functions aren't allowed (Array.sort(), Array.min(), etc.).

How do you know that array is in order? Go throuhg all numbers and check if next number is greater than the current number. If all numbers are greater, then the array is in order.