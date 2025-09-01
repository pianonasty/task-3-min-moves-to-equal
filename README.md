# task-4-min-moves-to-equal
Min Moves To Equalize Arrays

A Java program that calculates the minimum number of operations required to make all elements of an array equal, where each operation (move) can increment or decrement an element by 1.

Mathematical Foundation

The program utilizes a fundamental statistical principle: the median minimizes the sum of absolute deviations. The calculation formula is:
text

Minimum moves = Σ|xi - M|

where:

   xi = array elements

   M = median of the array

This property was proven in the 18th century and is widely used in statistics, machine learning, and operations research.

Algorithm

   1. Read numbers from the input file

   2. Sort the array to find the median

   3. Calculate the sum of absolute deviations from the median

   4. Check if the sum exceeds 20 moves

   5. Output the result or insufficiency message
