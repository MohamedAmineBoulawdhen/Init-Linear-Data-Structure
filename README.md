# Problem 1 - Summing Distinct Elements in Sets
## Problem Statement
Given two sets of elements, find the sum of all distinct elements from the set. In other words, find the sum of all elements which are present in either of the given set.

## Example
Set 1 : [3, 1, 7, 9], Set 2: [2, 4, 1, 9, 3]
Output: 13 (distinct elements 4, 7, 2 )

## Solution 1 with an Array
- Initialize sum = 0.
- Compare each element of set one with the second set.
- If element is not present in the second set, add that element to the sum.
- Repeat the above step for the second set.

## Solution 2 with an Hash Table
- Insert all the elements from both the sets with the element as key and its count (in both arrays).
- Iterate through the constructed map and sum all the elements with count = 1.

# Problem 2 - Summing Overlapping Elements in Sets
Given two sets of integers, write algorithms to print the sum of overlapping elements in two sets. The elements in each set are unique or there are no duplicates within a set.

## Example
Set 1: [12, 13, 6, 10]
Set 2: [13, 10, 16, 15]
Sum of overlapping elements: 46
Explanation: Common elements are 10, 13

## Solution 1 with an Array
- Initialize sum = 0.
- Compare each element of set one with the second set.
- If element is present in the second set, add that element to the sum.
- Repeat the above step for the second set.

## Solution 2 with an Hash Table
- Insert all the elements from both the sets with the element as key and its count (in both arrays).
- Iterate through the constructed map and sum all the elements with count > 1.

---
I hope this repository was helpful and provided you with a deeper understanding of finding the sum of distinct and overlapping elements in two sets. 
Don't hesitate to leave a star ⭐️ if you found it useful!
