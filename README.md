# Some algorithms

## MFU algorithms

### Longest increasing subsequence - O(N * logN)
- Keep a monotonic array  
- If the present element is freshly greatest append it.  
- Else, Binary search and update so that it reduces for further coming numbers  

## Intuition
127. Word ladder -> BFS because we don't want loop. And maybe optimize using A*
1293. Shortest path with obstracles move any direction. -> Perlocation problem BFS with eroding the graph.  
    Cat and Mouse -> DP on Graphs

## More dumbness
Overwhelmed by the name dutch national flag algorithm -> which is sorting 0,1,2 in O(n)
Also, levenshtein_distance -> which is edit distance: DP


## Sorting

### Minimum swaps required to sort array - cysclic sort
 - (if numbers arent contiguous, reduce it to contiguous mapping sorted order to 0 - N)
