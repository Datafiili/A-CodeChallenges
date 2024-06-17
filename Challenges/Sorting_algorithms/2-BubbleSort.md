# Bubble sort

As the name suggest, bubble sort works in a way where the numbers bubbles from bottom to top, into an order.
Easy steps for bubble sort:
1. Compare a number in the list to the next number on the list.
- If first number is greater than second, then swap them.
- If not, do nothing.
2. Then move to next number
Goint through all numbers with these steps, you will get largest number on the top. Now you have to repeat this process for each element in the array.

Optimization:
Every time a number has been pushed to the top, you don't have to move or compare that number to any other numbers.

Write a bubble sort function.