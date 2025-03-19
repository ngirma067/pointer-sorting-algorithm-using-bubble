# pointer-sorting-algorithm-using-bubble
## Complexity Analysis:
# Time Complexity:
- **Best Case (Already Sorted): O(n)**: — In this case, the algorithm only needs to traverse the array once without making any swaps. This can be achieved with an optimized version that stops if no swaps occur in a pass, but the provided implementation does not have this -optimization, so it would still run in O(n^2).
- **Average Case: O(n²)**: — In most cases, Bubble Sort needs to compare and potentially swap adjacent elements for every pair of elements in the array.
- **Worst Case (Array in Reverse Order): O(n²)**: — The worst case occurs when the array is in reverse order, and every pair of elements needs to be swapped
## Space Complexity:
- **Space Complexity: O(1)**: — The algorithm sorts the array in place, so it does not require any additional space aside from a few temporary variables (such as i, j, and the swap).
### Performance Summary:
In the C++ code above:
- **Best case**: If the array is already sorted or nearly sorted, the algorithm might complete in less time, but it is still O(n²) in the absence of early stopping optimizations.
- **Average and worst cases**: The algorithm performs a quadratic number of comparisons and swaps, leading to a time complexity of O(n²).
- **Memory Usage**: The space complexity is O(1) as it sorts in place.
