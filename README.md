# Data-Structures-Algorithms

## Google Interview List

### Arrays and Strings
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0003 | `Medium` | Longest Substring Without Repeating Characters | 15/08/2026 | ✅ Solved | 21 min | `Sliding Window` | Arrays and Strings | Sliding Window Optimized ✅ | Brute Force ❌ Sliding Window ❌ | When the number of characters is constrained don't use a hashmap use a List |
| LC-0011 | `Medium` | Container With Most Water | 08/08/2026 | ✅ Solved | 10 min | `Two Pointers` `Array` | Arrays and Strings | Two Pointer Approach ✅ | Brute Force ✅ | |
| LC-0043 | `Medium` | Multiply Strings | 15/08/2026 | ❌ Solved | ❌ min | `Math` `Strings` | Arrays and Strings || ||
| LC-0055 | `Medium` | Jump Game | 15/08/2026 | ✅ Solved | 32 min | `DP` `Array` | Arrays and Strings |Greedy ✅ | Backtracking ✅ DP Top-down ✅ DP Bottom-up ✅| ⚠️TC and SC |
| LC-0163 | `Easy` | Missing Ranges | 08/08/2026 | ✅ Solved | 7 min | `Array` | Arrays and Strings | Linear Scan ✅ |  | |
| LC-0681 | `Medium` | Next Closest Time | 14/08/2026 | ✅ Solved | 40 min | `Backtracking` | Arrays and Strings | Build From Allowed Digits ✅ | Simulation ❌  | Use nonlocal variable, to define variables in recursive functions|

### Trees and Graphs
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0124 | `Hard` | Binary Tree Maximum Path Sum | 17/08/2026 | ✅ Solved | 17 min | `DP` `DFS` `Binary Tree` | Trees and Graphs | Post Order DFS ✅ | | |
| LC-0127 | `Hard` | Word Ladder | 17/08/2026 | ✅ Solved | 40 min | `BFS` `Bidirectional Search` | Trees and Graphs | BFS ✅ |  Bidirectional BFS ❌ |  |
| LC-0394 | `Medium` | Decode String | 15/08/2026 | ❌ Solved | x min | `Stack` `Recursion` | Trees and Graphs | Recursion ❌ | Using Stack ❌ Using 2 Stack ❌ | |
| LC-0399 | `Medium` | Evaluate Division | 07/08/2026 | ⚠️ Solved | 50 min | `DFS` `Union-Find` | Trees and Graphs | Union-Find with Weights ❌ | Path Search in Graph ✅ | |
| LC-0543 | `Easy` | Diameter of Binary Tree | 10/08/2026 | ✅ Solved | 15 min | `Binary Tree` `DFS` | Trees and Graphs | Depth-first Search ✅ |   | |
| LC-0947 | `Medium` | Most Stones Removed with Same Row or Column | 08/08/2026 | ❌ Solved | 20 min | `Union-Find` `DFS` | Trees and Graphs | Disjoint Set Union (Optimized) ❌ | Depth First Search ❌, Disjoint Set Union ❌ |  |
| LC-0951 | `Medium` | Flip Equivalent Binary Trees | 08/08/2026 | ✅ Solved | 21 min | `Binary Tree` `Tree` | Trees and Graphs | Recursion (Top-down Traversal) ✅ |  Iterative DFS (using a Stack) ❌, Canonical Forms ❌ | The UNIQUENESS of the values of the tree is key for the performance. Optimal solution has **STACK OVERFLOW** risk. |

### Dynamic Programming
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0005 | `Medium` | Longest Palindromic Substring | 15/08/2026 | ⚠️ Solved | 30 min | `Two Pointers` `DP` | Dynamic Programming |Expand From Centers ✅ Manacher's Algorithm ❌ | Dynamic Programming ❌ Check All Substrings ❌ | |
| LC-0053 | `Medium` | Maximum Subarray | 18/08/2026 | ⚠️ Solved | 50 min | `DP` `Divide and Conquer` | Dynamic Programming |Kadane's Algorithm ❌ | Divide and Conquer ✅  Optimized Brute Force ✅ | |

### Sorting and Searching
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0004 | `Hard` | Median of Two Sorted Arrays | 18/08/2026 | ❌ Solved | 50 min | `Binary Search` `Divide and Conquer` | Sorting and Searching | A Better Binary Search ❌ | Merge Sort ❌  Binary Search ❌ | |
| LC-0056 | `Medium` | Merge Intervals | 09/08/2026 | ✅ Solved | 13 min | `Sorting` `Array` | Sorting and Searching | Sorting ✅ | Connected Components ❌ | TC and SP come from sorting |
| LC-0852 | `Medium` | Peak Index in a Mountain Array | 10/08/2026 | ✅ Solved | 12 min | `Binary Search` `Array` | Sorting and Searching | Binary Search ✅ | Linear Scan ❌ | Use int division for binary search while i < j: mid = (i + j) // 2 |

### Recursion
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0022 | `Medium` | Generate Parentheses | 08/08/2026 | ⚠️ Solved | 12 min | `Backtracking` `DP` | Recursion | Backtracking Keep Candidate Valid ✅ | Brute Force ❌, Divide and Conquer ❌ | Catalan Number for complexity ⚠️ |

### Design
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0359 | `Easy` | Logger Rate Limiter | 15/08/2026 | ⚠️ Solved | 9 min | `Hash Table` | Design | Queue + Set ❌ Hashtable / Dictionary ✅ |   | Use .get() for Hash Tables|

### Others
| Number | Difficulty | Name | Date of Last Attempt | Solved/Not | Best Time | Labels | Google List | Optimal Approach | Other Approaches | Comments |
|---|---|---|---|---|---|---|---|---|---|---|
| LC-0205 | `Easy` | Isomorphic Strings | 09/08/2026 | ✅ Solved | 11 min | `String` `Hast Table` | Others | Character Mapping with Dictionary ✅ | First occurence transformation ❌ | Use s_t = [None] * 128 and ord('a') for ASCII dictionaries |
| LC-0246 | `Easy` | Strobogrammatic Number | 03/08/2026 | ✅ Solved | 12 min | `Two Pointers` `Hash Table` `String` |Others| Two Pointers ✅ | Make a Rotated Copy ❌  | Code can be written in 2 lines |
| LC-0299 | `Medium` | Bulls and Cows | 08/08/2026 | ⚠️ Solved | 17 min | `Hash Table` | Others | One Pass ❌ | HashMap: Two Passes ✅ | When the number of characters is constrained don't use a hashmap use a List|

**Legend:** ✅ solved with best solution · ⚠️ solved, best solution pending · ❌ not solved
