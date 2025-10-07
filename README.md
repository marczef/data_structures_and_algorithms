# Data Structures & Algorithms

A comprehensive collection of data structures and algorithms for interview preparation and learning.

## Table of Contents
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)
- [Interview Preparation](#interview-preparation)

## Data Structures

### Linked List (Singly & Doubly)
**Key Concepts:** Non-contiguous memory, pointers/references, head & tail

**Core Operations:**
- Insert/Delete at head: O(1)
- Insert/Delete at tail (with tail pointer): O(1)
- Insert/Delete at arbitrary position (once node is found): O(1)
- Search: O(n)

**Must-Know Variations:**
- Detect and find cycle start (Floyd's Cycle-Finding Algorithm)
- Reverse a linked list (iterative and recursive)
- Find the k-th node from the end
- Merge two sorted linked lists

### Hash Table
**Key Concepts:** Hash function, collision resolution (chaining vs. open addressing), load factor and rehashing

**Core Operations:**
- Insert (Put): O(1) average, O(n) worst-case
- Search (Get): O(1) average, O(n) worst-case
- Delete: O(1) average, O(n) worst-case

**Must-Know Applications:**
- Frequency counting
- Storing mappings for O(1) lookups
- Duplicate detection

### Stack
**Key Concepts:** LIFO (Last-In, First-Out) order

**Core Operations:**
- Push: O(1)
- Pop: O(1)
- Peek: O(1)

**Must-Know Applications:**
- Function call stack (recursion)
- Expression evaluation and parsing
- Depth-First Search (DFS)
- Undo/Redo functionality

### Queue
**Key Concepts:** FIFO (First-In, First-Out) order

**Core Operations:**
- Enqueue (Add): O(1)
- Dequeue (Remove): O(1)
- Peek: O(1)

**Must-Know Variations:**
- Circular Queue: Efficient use of fixed memory
- Deque (Double-Ended Queue): Insert/delete from both ends
- Priority Queue

### Trees

#### Binary Tree
**Core Traversals** (all O(n) time):
- In-Order (Left, Root, Right)
- Pre-Order (Root, Left, Right)
- Post-Order (Left, Right, Root)
- Level-Order (Breadth-First, using a queue)

#### Binary Search Tree (BST)
**Key Concepts:** For any node, `left subtree < node < right subtree`

**Core Operations:**
- Search: O(h) - h is height of tree
- Insert: O(h)
- Delete: O(h)
- Find Min/Max: O(h)

**Must-Know Variations/Algorithms:**
- Validate if a tree is a BST
- In-order traversal gives sorted order
- Balanced BSTs (AVL, Red-Black Trees)

#### Heap / Priority Queue
**Key Concepts:** Complete binary tree, heap property (Min-Heap or Max-Heap)

**Core Operations:**
- Insert: O(log n)
- Extract-Min (or Extract-Max): O(log n)
- Peek (Find-Min): O(1)

**Must-Know Applications:**
- Implementing a Priority Queue
- Heap Sort
- Find Top K (or Bottom K) elements

#### Trie (Prefix Tree)
**Key Concepts:** Tree for storing strings, nodes represent characters, path from root represents a prefix

**Core Operations:**
- Insert a word: O(m) - m is length of word
- Search a word: O(m)
- Search a prefix: O(m)

**Must-Know Applications:**
- Autocomplete / Typeahead
- Spell checker
- IP Routing (Longest Prefix Matching)

### Graphs
**Key Concepts:** Vertices (Nodes) and Edges. Representations: Adjacency List, Adjacency Matrix

**Core Traversals:**
- Depth-First Search (DFS): Uses stack, good for exploring paths
- Breadth-First Search (BFS): Uses queue, good for shortest paths in unweighted graphs

**Must-Know Algorithms:**

#### Shortest Path
- **Dijkstra's Algorithm:** For weighted graphs with non-negative weights
- **Bellman-Ford:** For weighted graphs that may have negative weights

#### Minimum Spanning Tree (MST)
- **Prim's Algorithm:** Grows MST one vertex at a time
- **Kruskal's Algorithm:** Uses Union-Find to add edges

#### Other Graph Algorithms
- Topological Sort: For Directed Acyclic Graphs (DAGs)
- Detect cycles in directed/undirected graphs
- Find connected components
- Articulation Points (Cut Vertices)

### Advanced Data Structures
- **Union-Find (Disjoint Set):** Dynamic connectivity problems
- **Bloom Filter:** Probabilistic set membership

## Algorithms

### Binary Search
**Key Concept:** O(log n) search for sorted arrays

**Must-Know Variations:**
- Find first/last occurrence of element
- Find insertion point
- Binary Search on conceptual range

### Recursion & Backtracking
**Key Concepts:** Base case, recursive case, call stack

**Must-Know Problems:**
- Generate all subsets/combinations/permutations
- N-Queens problem
- Sudoku solver
- Rat in a Maze

### Dynamic Programming (DP)
**Key Concepts:** Breaking down problems into overlapping subproblems, memoization vs. tabulation

**Must-Know Problem Patterns:**
- **1D DP:** Fibonacci, Climbing Stairs
- **2D DP:** LCS, Edit Distance, Knapsack, Coin Change
- **Matrix/Grid DP:** Unique Paths, Minimum Path Sum
- **Interval DP:** Matrix Chain Multiplication

### String Algorithms
- Longest Palindromic Substring
- String Matching with Wildcard
- Edit Distance
- Longest Repeating Subsequence
- Count all distinct substrings
- KMP Algorithm for Pattern Searching
- Minimum characters to make string palindrome

### Sorting Algorithms
- QuickSort
- MergeSort
- HeapSort
- Counting Sort
- Radix Sort
- Bubble Sort
- Selection Sort
- Insertion Sort

### Searching Algorithms
- Linear Search
- Binary Search
- Ternary Search
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Fibonacci Search

### Greedy Algorithms
- Fractional Knapsack
- Huffman Coding
- Job Sequencing with Deadlines
- Activity Selection Problem
- Minimum number of Coins
- Minimum Platforms Required
- Connect n Ropes with Minimum Cost

### Tree Algorithms
- Lowest Common Ancestor (LCA)
- Diameter of Binary Tree
- Binary Tree Level Order Traversal
- Serialize and Deserialize Binary Tree
- Check if Binary Tree is BST
- Inorder Traversal without Recursion
- Convert Binary Tree to Doubly Linked List
- Check if Two Trees are Identical

### Graph Algorithms
- Dijkstra's Algorithm
- Kruskal's Algorithm
- Topological Sorting
- Bellman-Ford Algorithm
- Floyd Warshall Algorithm
- Prim's Algorithm
- Detect Cycle in Directed Graph
- Articulation Points

### Bit Manipulation
- Find the Only Non-Repeating Element
- Count Total Set Bits
- Maximum XOR of Two Numbers
- Find two non-repeating elements
- Check if number is sparse
- Count set bits from 1 to n
- Maximum subarray XOR
- Power of two check

## Interview Preparation

### Strategy
1. **Foundation First:** Master core data structures implementation
2. **Pattern Recognition:** Categorize problems by technique
3. **Complexity Analysis:** Always articulate time/space complexity
4. **Practice:** Solve problems on LeetCode, HackerRank
5. **Mock Interviews:** Practice explaining thought process aloud

### Key Focus Areas
- Graphs and Graph Traversals
- Dynamic Programming
- Tree Operations
- System Design Principles
- Time/Space Complexity Analysis

### Resources
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [LeetCode](https://leetcode.com/)
- [Cracking the Coding Interview]
- [Introduction to Algorithms]