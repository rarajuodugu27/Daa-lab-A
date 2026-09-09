# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search

# PRACTICAL 3 : Min-Heap and Max-Heap Sort
Description:

This project implements Heap Sort in Python using heapq.

Min-Heap: Sorts elements in ascending order.
Max-Heap: Sorts elements in descending order.
Features
Takes user input for array elements.
Uses heapq.heapify() and heapq.heappop().
Measures execution time using time.perf_counter().
Displays time complexity.
Example

Min-Heap:

Input: 25, 14, 36, 85, 96
Output: [14, 25, 36, 85, 96]

Max-Heap:

Input: 25, 78, 89, 45, 56, 33
Output: [89, 78, 56, 45, 33, 25]
Complexity
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Space Complexity: O(n)
Requirements
Python 3
heapq and time modules (built-in)
Conclusion

The program demonstrates how Min-Heap and Max-Heap can be used to efficiently sort an array in ascending and descending order.


# SUMMARY OF PRACT-4: 
In this practical, we learned how to find the factorial of a number using two different methods: iterative and recursive. In the iterative method, we use a loop to multiply the numbers from 1 to the given number. In the recursive method, the function calls itself with a smaller value until it reaches the base condition. Both methods give the same factorial result, but they work in different ways. CONCLUSION: From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem. CONCLUSION: From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods ar

practical-5:Knapsack Problem
This project is a Python program that solves the 0/1 Knapsack Problem using Dynamic Programming. The program takes the number of items, their weights, values, and the maximum capacity of the knapsack as input. It then finds the maximum value that can be carried without exceeding the given capacity. The program also displays the selected items and the execution time. This project is simple and useful for understanding the basic concept of Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named knapsack.py and run it using the command python knapsack.py in the terminal.

Example

For 4 items with weights 2, 3, 4, 5 and values 3, 4, 5, 6, with a knapsack capacity of 5, the maximum value is 7 and items 1 and 2 are selected.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the 0/1 Knapsack Problem. It helps in finding the best combination of items while keeping the total weight within the given capacity. The project is simple and helpful for learning Python and Dynamic Programming.

practical-7:Coin Change Problem using Dynamic Programming
This project is a Python program that solves the Coin Change Problem using Dynamic Programming. The program takes the number of coins, the value of each coin, and the required amount as input. It finds the minimum number of coins needed to make the given amount. If the amount cannot be made using the given coins, the program returns -1. For example, if the coins are 1, 2, and 5 and the amount is 15, the minimum number of coins required is 3. The time complexity of the program is O(n * amount) and the space complexity is O(amount). This project is simple and useful for understanding Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named coin_change.py and run it using the command python coin_change.py in the terminal.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the Coin Change Problem efficiently. It helps find the minimum number of coins required to make a given amount and is useful for understanding the basic concepts of optimization and Dynamic Programming.
