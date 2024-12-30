This month, I started reading Grokking Algorithms by Aditya Bhargava (Second Edition) to deepen my understanding of core algorithmic concepts. The book introduces algorithms with clear explanations and visual diagrams, making it beginner-friendly and engaging.


Chapter 1: Introduction to Algorithms
Algorithms are step-by-step instructions for solving problems. They’re important for making programs efficient. Binary search is introduced as a way to quickly find an item in a sorted list by repeatedly dividing the list in half. For example, findinga name in a sorted phone book. Big O notation is used to measure efficiency, with binary search having 
O(logn), which is much faster than checking every item.

Chapter 2: Selection Sort
Selection sort is a simple sorting algorithm. It works by repeatedly finding the smallest item in a list and adding it to a new sorted list. The steps are:

Find the smallest item.
Add it to the sorted list.
Repeat until everything is sorted.
It has a time complexity of 
𝑂(𝑛2), which is slow for large datasets but easy to understand.

Chapter 3: Recursion
Recursion is when a function calls itself to solve smaller versions of the same problem. Examples include calculating factorials or navigating file systems. Recursion works by breaking a problem into smaller pieces and stopping at a "base case." It’s powerful but can be inefficient if not used carefully (e.g., too many duplicate calculations).

Chapter 4: Divide and Conquer
Divide and conquer is a strategy for solving problems by splitting them into smaller parts, solving those, and then combining the results. Quick sort is a good example:

Pick a pivot and split the array into two parts (less than and greater than the pivot).
Recursively sort each part.
Combine the sorted parts.
Quick sort has an average time complexity of 
𝑂(𝑛log⁡𝑛), making it much faster than selection sort for large datasets.
