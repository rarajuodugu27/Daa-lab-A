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



# SUMMARY OF PRACT-7: Coin Change Problem using Dynamic Programming

This project is a Python program that solves the Coin Change Problem using Dynamic Programming. The program takes the number of coins, the value of each coin, and the required amount as input. It finds the minimum number of coins needed to make the given amount. If the amount cannot be made using the given coins, the program returns -1. For example, if the coins are 1, 2, and 5 and the amount is 15, the minimum number of coins required is 3. The time complexity of the program is O(n * amount) and the space complexity is O(amount). This project is simple and useful for understanding Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named coin_change.py and run it using the command python coin_change.py in the terminal.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the Coin Change Problem efficiently. It helps find the minimum number of coins required to make a given amount and is useful for understanding the basic concepts of optimization and Dynamic Programming.




# SUMMARY OF PRACT-5: Knapsack Problem

This project is a Python program that solves the 0/1 Knapsack Problem using Dynamic Programming. The program takes the number of items, their weights, values, and the maximum capacity of the knapsack as input. It then finds the maximum value that can be carried without exceeding the given capacity. The program also displays the selected items and the execution time. This project is simple and useful for understanding the basic concept of Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named knapsack.py and run it using the command python knapsack.py in the terminal.

Example

For 4 items with weights 2, 3, 4, 5 and values 3, 4, 5, 6, with a knapsack capacity of 5, the maximum value is 7 and items 1 and 2 are selected.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the 0/1 Knapsack Problem. It helps in finding the best combination of items while keeping the total weight within the given capacity. The project is simple and helpful for learning Python and Dynamic Programming.

# Practical 6: Chain Matrix Multiplication

## Aim
To implement Chain Matrix Multiplication using Dynamic Programming in Python.

##  Summary
- Chain Matrix Multiplication is an optimization problem.
- Dynamic Programming is used to find the optimal multiplication order.
- The program accepts matrix dimensions as **user input**.
- It calculates the **minimum number of scalar multiplications**.
- Intermediate results are stored in a DP table.
- The program also measures the **execution time**.
- **Time Complexity:** `O(n³)`
- **Space Complexity:** `O(n²)`
- The implementation is written in **Python**.
- The practical demonstrates the application of Dynamic Programming for optimization.



##practical 8:Implementation of Graph and Searching (DFS and BFS)

SUMMARY

Graph traversal is an important technique used to visit all the vertices of a graph systematically. DFS explores a graph deeply by visiting a vertex and then recursively visiting its unvisited neighbors. BFS explores the graph level by level using a queue data structure. Both DFS and BFS have a time complexity of O(V + E), where V is the number of vertices and E is the number of edges. These searching techniques are widely used in path finding, network analysis, and many other computer science applications.

CONCLUSION :

The graph traversal program successfully implements both DFS and BFS searching techniques using Python. DFS uses a depth-based approach, while BFS visits vertices level by level. Both methods efficiently traverse the vertices and edges of a graph. The program accepts user input, making it flexible for different graph structures and starting vertices. Thus, DFS and BFS are useful and fundamental techniques for solving various graph-based problems.

practical-9 PRIM's Algorithm

Prim's Algorithm is a greedy algorithm used to find the Minimum Spanning Tree (MST) of a connected, weighted, undirected graph. It starts with an arbitrary vertex and repeatedly selects the minimum-weight edge that connects a visited vertex to an unvisited vertex without forming a cycle. This process continues until all vertices are included in the spanning tree, resulting in the minimum total edge weight. Prim's Algorithm is widely used in network design and optimization problems.

practical-10 KRUSKAL's Algorithm

Kruskal's Algorithm is a greedy algorithm used to find the Minimum Spanning Tree (MST) of a weighted, undirected graph. It works by sorting all edges in ascending order of their weights and selecting the smallest edges one by one, ensuring that no cycle is formed. The process continues until the spanning tree contains exactly (V-1) edges, where (V) is the number of vertices. Kruskal's Algorithm is useful in network design and optimization problems where minimizing the total connection cost is important.

# Practical 11: Floyd-Warshall Algorithm (All-Pairs Shortest Path)
This directory contains the Python implementation of the Floyd-Warshall Algorithm for finding All-Pairs Shortest Paths in a directed, weighted graph using Dynamic Programming.

📌 Problem Overview & Paradigm
Given a directed weighted graph 
G
=
(
V
,
E
)
 represented as an adjacency matrix, compute the shortest path distances between every pair of vertices 
i
,
j
∈
V
.

Method Implemented
Floyd-Warshall Tabulation (floyd_warshall(graph))
Maintains a 2D distance matrix 
d
i
s
t
[
i
]
[
j
]
 and a predecessor matrix 
n
e
x
t
n
o
d
e
[
i
]
[
j
]
.
Iterates through all possible intermediate vertices 
k
∈
0
,
1
,
…
,
V
−
1
 and updates paths:
Recurrence Relation: 
D
(
k
)
[
i
]
[
j
]
=
min
(
D
(
k
−
1
)
[
i
]
[
j
]
,
;
D
(
k
−
1
)
[
i
]
[
k
]
+
D
(
k
−
1
)
[
k
]
[
j
]
)
Time Complexity: 
O
(
V
3
)
 (three nested loops over vertices).
Space Complexity: 
O
(
V
2
)
 for intermediate matrices.
⚡ Complexity Summary
Approach	Best Case	Average Case	Worst Case	Auxiliary Space	Paradigm	Guarantees Optimality?
Floyd-Warshall (DP)	
O
(
V
3
)
O
(
V
3
)
O
(
V
3
)
O
(
V
2
)
Dynamic Programming	✅ Yes (Detects negative cycles)
💻 How to Run
Open your terminal or command prompt.
Navigate to the practical_11 directory:
cd practical_11
Execute the Python script:
python floyd_warshall.py
📋 Sample Output
==================================================
      FLOYD-WARSHALL ALL-PAIRS SHORTEST PATH      
==================================================
Default Graph Adjacency Weight Matrix:

========== ALL-PAIRS SHORTEST DISTANCE MATRIX ==========
From\To Node    0   Node    1   Node    2   Node    3
-----------------------------------------------------
Node 0          0          3        INF          7
Node 1          8          0          2        INF
Node 2          5        INF          0          1
Node 3          2        INF        INF          0
-----------------------------------------------------

Use custom input? (y/N): n

--- Running Floyd-Warshall Dynamic Programming Solver ---

========== ALL-PAIRS SHORTEST DISTANCE MATRIX ==========
From\To Node    0   Node    1   Node    2   Node    3
-----------------------------------------------------
Node 0          0          3          5          6
Node 1          5          0          2          3
Node 2          3          6          0          1
Node 3          2          5          7          0
-----------------------------------------------------

========== SAMPLE PATH RECONSTRUCTIONS ==========
Source   -> Target   | Cost   | Path                
------------------------------------------------
Node 0   -> Node 1   | 3      | 0 -> 1              
Node 0   -> Node 2   | 5      | 0 -> 1 -> 2         
Node 0   -> Node 3   | 6      | 0 -> 1 -> 2 -> 3    
...

========== RESULTS SUMMARY ==========
Total Vertices (V)    : 4
Execution Time        : 19800.00 ns
======================================
📖 Key Takeaways & Conclusion
All-Pairs Distance Matrix:
Unlike Dijkstra's or Bellman-Ford algorithms which compute single-source shortest paths, Floyd-Warshall computes shortest paths between all pairs of nodes simultaneously in 
O
(
V
3
)
 time.
Dense Graph Suitability:
Highly effective for dense graphs (
E
≈
V
2
) where running Dijkstra 
V
 times would take 
O
(
V
E
log
⁡
V
)
≈
O
(
V
3
log
⁡
V
)
.
# Practical 12: Travelling Salesman Problem (Dynamic Programming - Held-Karp Algorithm)
This directory contains the Python implementation of the Travelling Salesman Problem (TSP) solved using the Held-Karp Dynamic Programming algorithm with Bitmask State Representation, alongside a comparison against the naive Brute-Force Permutation method.

📌 Problem Overview & Paradigm
Given a set of 
N
 cities and pairwise distances 
d
(
i
,
j
)
 between them, find the minimum cost tour that starts at a designated origin city (e.g., City 0), visits every other city exactly once, and returns to the origin city.

Methods Implemented
Held-Karp Dynamic Programming (tsp_held_karp(matrix))

Uses bitmasks to represent subsets of visited cities. State is defined as 
(
S
,
u
)
, representing the minimum cost to complete the tour starting at city 
u
 having visited city subset 
S
.
Recurrence Relation: 
g
(
S
,
u
)
=
min
v
∉
S
(
d
(
u
,
v
)
+
g
(
S
∪
v
,
v
)
)
Base Case: 
g
(
All Cities
,
u
)
=
d
(
u
,
0
)
 (return cost to start city 0).
Time Complexity: 
O
(
N
2
⋅
2
N
)
Space Complexity: 
O
(
N
⋅
2
N
)
Brute-Force Permutations (tsp_brute_force(matrix))

Generates all 
(
N
−
1
)
!
 possible tour permutations.
Time Complexity: 
O
(
N
!
)
Space Complexity: 
O
(
N
)
⚡ Complexity Summary
Approach	Best Case	Average Case	Worst Case	Auxiliary Space	Paradigm	Guarantees Optimality?
Held-Karp DP	
O
(
N
2
⋅
2
N
)
O
(
N
2
⋅
2
N
)
O
(
N
2
⋅
2
N
)
O
(
N
⋅
2
N
)
Dynamic Programming (Bitmask)	✅ Yes (Always Optimal)
Brute-Force	
O
(
N
!
)
O
(
N
!
)
O
(
N
!
)
O
(
N
)
Exhaustive Search	✅ Yes (Always Optimal)
💻 How to Run
Open your terminal or command prompt.
Navigate to the practical_12 directory:
cd practical_12
Execute the Python script:
python travelling_salesman.py
📋 Sample Output
==================================================
   TRAVELLING SALESMAN PROBLEM (HELD-KARP DP)    
==================================================
Default Distance Matrix (4 Cities):
From\To     City 0    City 1    City 2    City 3
--------------------------------------------------
City 0           0        10        15        20
City 1          10         0        35        25
City 2          15        35         0        30
City 3          20        25        30         0
--------------------------------------------------

Use custom input? (y/N): n

--- Running Dynamic Programming (Held-Karp) Solver ---
--- Running Brute-Force Permutation Solver ---

========== OPTIMAL TOUR PATH ==========
Tour Path : City 0 -> City 1 -> City 3 -> City 2 -> City 0

========== RESULTS & METHOD COMPARISON ==========
Method          | Min Tour Cost   | Execution Time (ns) 
-------------------------------------------------------
Held-Karp (DP)  | 80              | 36400.00            
Brute-Force     | 80              | 28900.00            
=======================================================
📖 Key Takeaways & Conclusion
Exponential Optimization:
The Held-Karp DP algorithm reduces TSP complexity from factorial time 
O
(
N
!
)
 to exponential time 
O
(
N
2
2
N
)
.
Practical Applicability:
Held-Karp makes exact TSP solutions feasible for up to 
N
≈
20
 cities, whereas Brute-Force stalls for 
N
≥
12
.
