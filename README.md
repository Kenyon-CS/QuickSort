# QuickSort

# How Quick Sort Works
## Step-by-Step Process:
1. **Choose a Pivot**: Select a pivot element (in this case, the last element).
2. **Partitioning**: Rearrange elements around the pivot so that elements less than the pivot are on the left and elements greater are on the right.
3. **Recursively Sort Partitions**: Recursively apply Quick Sort on the left and right partitions until the entire array is sorted.

## Quick Sort Characteristics:

**Average Time Complexity**: 𝑂(𝑛log 𝑛), but it can degrade to 𝑂(𝑛<sup>2</sup>) if the pivot selection is poor (e.g., always choosing the smallest or largest element in a sorted array).
**Space Complexity**: 𝑂(log 𝑛) for the recursive stack.
**Stability**: Quick Sort is not stable, as it may reorder equal elements.
This example demonstrates the fundamental steps of Quick Sort, showcasing its divide-and-conquer approach and the use of recursion to sort an array efficiently.
