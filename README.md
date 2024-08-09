# data-structure
# Time and Space Complexity Concept 

Time Complexity: Measures the amount of time an algorithm takes to run as a function of the size of its input.
Space Complexity: Measures the amount of memory an algorithm uses as a function of the size of its input.

# Big O Notation
Big O (O): Describes the upper bound of an algorithm's runtime, i.e., the worst-case scenario.
Common Big O Notations:
O(1): Constant time (e.g., accessing an array element).
O(log n): Logarithmic time (e.g., binary search).
O(n): Linear time (e.g., iterating through an array).
O(n log n): Linearithmic time (e.g., merge sort).
O(n^2): Quadratic time (e.g., bubble sort).
O(2^n): Exponential time (e.g., recursive algorithms for Fibonacci numbers).
O(n!): Factorial time (e.g., generating all permutations).

# Best Practices
Avoid Nested Loops: If possible, avoid nested loops to prevent quadratic or higher time complexities.
Use Efficient Data Structures: Choosing the right data structure (e.g., hash tables for O(1) lookups) can significantly reduce time complexity.
Recursion with Memoization: Use memoization to store previously calculated results and avoid repeated work.

# Asymptotic Analysis
Best Case: The scenario where the algorithm performs the minimum number of operations.
Worst Case: The scenario where the algorithm performs the maximum number of operations.
Average Case: The expected time complexity for a random input.
