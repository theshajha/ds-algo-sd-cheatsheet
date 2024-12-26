# Big O Notation
Details from [Big O Notation](https://www.bigocheatsheet.com/) and [Data Structures and Algorithms Cheat Sheet](https://www.clear.rice.edu/comp160/data_cheat.html)


## Sorting Algorithms

| Algorithm | Space Complexity | Time Complexity (Best) | Time Complexity (Average) | Time Complexity (Worst) |
|-----------|-----------------|----------------------|------------------------|----------------------|
| Insertion Sort | O(1) | O(n) | O(n²) | O(n²) |
| Selection Sort | O(1) | O(n²) | O(n²) | O(n²) |
| Smooth Sort | O(1) | O(n) | O(n log n) | O(n log n) |
| Bubble Sort | O(1) | O(n) | O(n²) | O(n²) |
| Shell Sort | O(1) | O(n) | O(n log n²) | O(n log n²) |
| Mergesort | O(n) | O(n log n) | O(n log n) | O(n log n) |
| Quicksort | O(log n) | O(n log n) | O(n log n) | O(n log n) |
| Heapsort | O(1) | O(n log n) | O(n log n) | O(n log n) |

## Data Structures Comparison

| Data Structure | Average Case ||| Worst Case |||
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| | Search | Insert | Delete | Search | Insert | Delete |
|Array| O(n) | N/A | N/A | O(n) | N/A | N/A |
|Sorted Array| O(log n) | O(n) | O(n) | O(log n) | O(n) | O(n) |
|Linked List| O(n) | O(1) | O(1) | O(n) | O(1) | O(1) |
|Doubly Linked List| O(n) | O(1) | O(1) | O(n) | O(1) | O(1) |
|Stack| O(n) | O(1) | O(1) | O(n) | O(1) | O(1) |
|Hash table| O(1) | O(1) | O(1) | O(n) | O(n) | O(n) |
|Binary Search Tree| O(log n) | O(log n) | O(log n) | O(n) | O(n) | O(n) |
|B-Tree| O(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(log n) |
|Red-Black tree| O(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(log n) |
|AVL Tree| O(log n) | O(log n) | O(log n) | O(log n) | O(log n) | O(log n) |


## Time Complexity Graph
![Big O Notation Graph](https://cooervo.github.io/Algorithms-DataStructures-BigONotation/images/graphs/comparison.svg)

## Execution Time by Input Size

| n | log n | n | n log n | n² | 2ⁿ | n! |
|---:|---:|---:|---:|---:|---:|---:|
| 10 | 0.003ns | 0.01ns | 0.033ns | 0.1ns | 1ns | 3.65ms |
| 20 | 0.004ns | 0.02ns | 0.086ns | 0.4ns | 1ms | 77years |
| 30 | 0.005ns | 0.03ns | 0.147ns | 0.9ns | 1sec | 8.4x10¹⁵yrs |
| 40 | 0.005ns | 0.04ns | 0.213ns | 1.6ns | 18.3min | -- |
| 50 | 0.006ns | 0.05ns | 0.282ns | 2.5ns | 13days | -- |
| 100 | 0.07ns | 0.1ns | 0.644ns | 0.10ns | 4x10¹³yrs | -- |
| 1,000 | 0.010ns | 1.00ns | 9.966ns | 1ms | -- | -- |
| 10,000 | 0.013ns | 10ns | 130ns | 100ms | -- | -- |
| 100,000 | 0.017ns | 0.10ms | 1.67ms | 10sec | -- | -- |
| 1,000,000 | 0.020ns | 1ms | 19.93ms | 16.7min | -- | -- |
| 10,000,000 | 0.023ns | 0.01sec | 0.23ms | 1.16days | -- | -- |
| 100,000,000 | 0.027ns | 0.10sec | 2.66sec | 115.7days | -- | -- |
| 1,000,000,000 | 0.030ns | 1sec | 29.90sec | 31.7 years | -- | -- |