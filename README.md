# Data-Structures-Algorithms

## Google Interview List

### Arrays and Strings
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0003 | `Medium` | Longest Substring Without Repeating Characters | 15/08/2026 | ✅ | 21 min | `Sliding Window` | Sliding Window Optimized ✅ | Brute Force ❌ Sliding Window ❌ | When the number of characters is constrained don't use a hashmap use a List |
| LC-0011 | `Medium` | Container With Most Water | 08/08/2026 | ✅ | 10 min | `Two Pointers` `Array` | Two Pointer Approach ✅ | Brute Force ✅ | |
| LC-0043 | `Medium` | Multiply Strings | 15/08/2026 | ❌ | ❌ min | `Math` `Strings` || ||
| LC-0055 | `Medium` | Jump Game | 15/08/2026 | ✅ | 32 min | `DP` `Array` | Greedy ✅ | Backtracking ✅ DP Top-down ✅ DP Bottom-up ✅| ⚠️TC and SC |
| LC-0163 | `Easy` | Missing Ranges | 08/08/2026 | ✅ | 7 min | `Array` | Linear Scan ✅ |  | |
| LC-0681 | `Medium` | Next Closest Time | 14/08/2026 | ✅ | 40 min | `Backtracking` | Build From Allowed Digits ✅ | Simulation ❌  | Use nonlocal variable, to define variables in recursive functions|

### Trees and Graphs
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0124 | `Hard` | Binary Tree Maximum Path Sum | 17/08/2026 | ✅ | 17 min | `DP` `DFS` `Binary Tree` | Post Order DFS ✅ | | |
| LC-0127 | `Hard` | Word Ladder | 17/08/2026 | ✅ | 40 min | `BFS` `Bidirectional Search` | BFS ✅ |  Bidirectional BFS ❌ |  |
| LC-0394 | `Medium` | Decode String | 15/08/2026 | ❌ | x min | `Stack` `Recursion` | Recursion ❌ | Using Stack ❌ Using 2 Stack ❌ | |
| LC-0399 | `Medium` | Evaluate Division | 07/08/2026 | ⚠️ | 50 min | `DFS` `Union-Find` | Union-Find with Weights ❌ | Path Search in Graph ✅ | |
| LC-0543 | `Easy` | Diameter of Binary Tree | 10/08/2026 | ✅ | 15 min | `Binary Tree` `DFS` | Depth-first Search ✅ |   | |
| LC-0947 | `Medium` | Most Stones Removed with Same Row or Column | 08/08/2026 | ❌ | 20 min | `Union-Find` `DFS` | Disjoint Set Union (Optimized) ❌ | Depth First Search ❌, Disjoint Set Union ❌ |  |
| LC-0951 | `Medium` | Flip Equivalent Binary Trees | 08/08/2026 | ✅ | 21 min | `Binary Tree` `Tree` | Recursion (Top-down Traversal) ✅ |  Iterative DFS (using a Stack) ❌, Canonical Forms ❌ | The UNIQUENESS of the values of the tree is key for the performance. Optimal solution has **STACK OVERFLOW** risk. |

### Dynamic Programming
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0005 | `Medium` | Longest Palindromic Substring | 15/08/2026 | ⚠️ | 30 min | `Two Pointers` `DP` | Expand From Centers ✅ Manacher's Algorithm ❌ | Dynamic Programming ❌ Check All Substrings ❌ | |
| LC-0053 | `Medium` | Maximum Subarray | 18/08/2026 | ⚠️ | 50 min | `DP` `Divide and Conquer` | Kadane's Algorithm ❌ | Divide and Conquer ✅  Optimized Brute Force ✅ | |

### Sorting and Searching
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0004 | `Hard` | Median of Two Sorted Arrays | 18/08/2026 | ❌ | 50 min | `Binary Search` `Divide and Conquer` | A Better Binary Search ❌ | Merge Sort ❌  Binary Search ❌ | |
| LC-0056 | `Medium` | Merge Intervals | 09/08/2026 | ✅ | 13 min | `Sorting` `Array` | Sorting ✅ | Connected Components ❌ | TC and SP come from sorting |
| LC-0852 | `Medium` | Peak Index in a Mountain Array | 10/08/2026 | ✅ | 12 min | `Binary Search` `Array` | Binary Search ✅ | Linear Scan ❌ | Use int division for binary search while i < j: mid = (i + j) // 2 |

### Recursion
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0022 | `Medium` | Generate Parentheses | 08/08/2026 | ⚠️ | 12 min | `Backtracking` `DP` | Backtracking Keep Candidate Valid ✅ | Brute Force ❌, Divide and Conquer ❌ | Catalan Number for complexity ⚠️ |

### Design
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0359 | `Easy` | Logger Rate Limiter | 15/08/2026 | ⚠️ | 9 min | `Hash Table` | Queue + Set ❌ Hashtable / Dictionary ✅ |   | Use .get() for Hash Tables|

### Others
| # | Difficulty | Name | Last Attempt | Status | Best Time | Labels | Optimal | Others | Comments |
|---|---|---|---|---|---|---|---|---|---|
| LC-0205 | `Easy` | Isomorphic Strings | 09/08/2026 | ✅ | 11 min | `String` `Hast Table` | Character Mapping with Dictionary ✅ | First occurence transformation ❌ | Use s_t = [None] * 128 and ord('a') for ASCII dictionaries |
| LC-0246 | `Easy` | Strobogrammatic Number | 03/08/2026 | ✅ | 12 min | `Two Pointers` `Hash Table` `String` | Two Pointers ✅ | Make a Rotated Copy ❌  | Code can be written in 2 lines |
| LC-0299 | `Medium` | Bulls and Cows | 08/08/2026 | ⚠️ | 17 min | `Hash Table` | One Pass ❌ | HashMap: Two Passes ✅ | When the number of characters is constrained don't use a hashmap use a List|

**Legend:** ✅ solved with best solution · ⚠️ solved, best solution pending · ❌ not solved
