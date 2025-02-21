# dsa

**1-week ultra-comprehensive CP/DSA roadmap**

This schedule is **intensive**, covering key concepts with **zero fluff**. You’ll need around **8-10 hours daily** for deep mastery.  

---

### **🗓️ 1-Week CP/DSA Mastery Plan**  
**Goal:** After completing this, you should be able to solve **most** LeetCode problems **independently** and perform well in **competitive programming (CP)** contests.

---


## 📑 Table of Contents
- [📍 Day 1: Essential Fundamentals & STL Mastery](#-day-1-essential-fundamentals--stl-mastery)
- [📍 Day 2: Mastering Arrays, Strings & Two Pointers](#-day-2-mastering-arrays-strings--two-pointers)
- [📍 Day 3: Mastering Recursion & Backtracking](#-day-3-mastering-recursion--backtracking)
- [📍 Day 4: Mastering Graphs & Trees (DSA Heavyweight Topics)](#-day-4-mastering-graphs--trees-dsa-heavyweight-topics)
- [📍 Day 5: Mastering Dynamic Programming (DP)](#-day-5-mastering-dynamic-programming-dp)
- [📍 Day 6: Mastering Advanced Topics](#-day-6-mastering-advanced-topics)
- [📍 Day 7: Practice, Revision & Speed Optimization](#-day-7-practice-revision--speed-optimization)
- [🎯 Final Notes](#-final-notes)
- [What is STL?](#what-is-stl)
  - [📌 Components of STL](#components-of-stl)
  - [📍 1. Algorithms in STL](#-1-algorithms-in-stl)
  - [📍 2. Containers (Data Structures in STL)](#-2-containers-data-structures-in-stl)
  - [📍 3. Iterators (Access Elements Efficiently)](#-3-iterators-access-elements-efficiently)

---

### **📍 Day 1: Essential Fundamentals & STL Mastery**  
> **Goal:** Master basic data structures, STL, and time complexity.  
⏳ **Time Allocation:** ~8-10 hours  

✅ **1️⃣ Complexity Analysis & Problem Solving Approach**  
   - **Big O Notation** (O(1), O(log N), O(N), O(N log N), O(N²), etc.)  
   - Best, Worst, and Average Case Analysis  
   - Identifying **brute force vs optimized** approaches  

✅ **2️⃣ Sorting Algorithms (Learn + Implement)**  
   - **Selection Sort** (O(N²))  
   - **Bubble Sort** (O(N²))  
   - **Insertion Sort** (O(N²))  
   - **Merge Sort** (O(N log N))  
   - **Quick Sort** (O(N log N), worst O(N²))  
   - **Counting Sort** (O(N + K)) [for small integer ranges]  
   - **Bucket/Radix Sort** (for numbers with fixed length)  

✅ **3️⃣ Mastering C++ STL (Competitive Edge)**  
   - **Vectors, Sets, Maps, Queues, Deques, Priority Queues**  
   - Sorting with Custom Comparators (`sort(v.begin(), v.end(), cmp)`)  
   - **Binary Search (STL)**: `lower_bound()`, `upper_bound()`  
   - **Pairs & Tuples for CP**  
   - **Modular Arithmetic & Fast Exponentiation (`powmod`)**  
   - **Two-pointer technique, Sliding Window**

✅ **Practice:**  
   - **LeetCode Easy:** (Arrays & Sorting)  
   - **AtCoder Beginner Contests**

---

### **📍 Day 2: Mastering Arrays, Strings & Two Pointers**  
> **Goal:** Solve all array-based problems using optimal techniques.  
⏳ **Time Allocation:** ~8-10 hours  

✅ **1️⃣ Arrays: Sliding Window, Prefix Sum, Kadane’s Algorithm**  
   - **Prefix Sum & Difference Array**  
   - **Kadane’s Algorithm (Max Subarray Sum in O(N))**  
   - **Sliding Window Technique**  
   - **Two-pointer approach**  

✅ **2️⃣ Strings: Pattern Matching & Manipulation**  
   - **KMP Algorithm (O(N))**  
   - **Z-Algorithm (Pattern Matching, O(N))**  
   - **Manacher’s Algorithm (Longest Palindromic Substring, O(N))**  
   - **Rabin-Karp (Substring Search, O(N))**  
   - **Trie Data Structure (for Prefix Matching)**  

✅ **Practice:**  
   - **LeetCode Medium:** Sliding Window & Two Pointers  
   - **Codeforces Div 2 Contests**

---

### **📍 Day 3: Mastering Recursion & Backtracking**  
> **Goal:** Build deep recursion & problem-solving skills.  
⏳ **Time Allocation:** ~8-10 hours  

✅ **1️⃣ Recursion: Core Concepts**  
   - **Base Case & Recursive Trees**  
   - **Tail Recursion vs Non-Tail Recursion**  
   - **Recursion with Memoization (Top-Down DP)**  

✅ **2️⃣ Backtracking (Must-Know Problems)**  
   - **N-Queens Problem**  
   - **Sudoku Solver**  
   - **Word Search in a Grid**  
   - **Generating All Subsets/Subsequences**  
   - **Permutation & Combination Problems**  

✅ **Practice:**  
   - **LeetCode Hard:** Recursion & Backtracking  
   - **Codeforces Div 2 & 3 Contests**

---

### **📍 Day 4: Mastering Graphs & Trees (DSA Heavyweight Topics)**  
> **Goal:** Become fluent in Graph & Tree algorithms.  
⏳ **Time Allocation:** ~10 hours  

✅ **1️⃣ Graph Traversal (BFS & DFS)**  
   - **Graph Representation (Adj List vs Adj Matrix)**  
   - **DFS & BFS (Iterative + Recursive)**  
   - **Cycle Detection (Directed & Undirected Graphs)**  

✅ **2️⃣ Shortest Path Algorithms**  
   - **Dijkstra’s Algorithm (Single Source Shortest Path O((V + E) logV))**  
   - **Bellman-Ford Algorithm (Handles Negative Weights, O(VE))**  
   - **Floyd-Warshall Algorithm (All-Pairs Shortest Path, O(V³))**  

✅ **3️⃣ MST & Disjoint Set Union (DSU)**  
   - **Kruskal’s Algorithm (O(E logE))**  
   - **Prim’s Algorithm (O(E logV))**  
   - **Union-Find (Path Compression + Rank Optimization)**  

✅ **4️⃣ Tree Basics & Advanced**  
   - **Binary Trees: DFS, BFS, Level Order, Diameter, LCA**  
   - **Binary Search Trees (Insertion, Deletion, Range Queries)**  
   - **Segment Tree & Fenwick Tree (O(log N) Range Queries)**  

✅ **Practice:**  
   - **LeetCode Hard:** Graphs & Trees  
   - **Codeforces Div 1 Contests**  

---

### **📍 Day 5: Mastering Dynamic Programming (DP)**  
> **Goal:** Solve DP problems without hesitation.  
⏳ **Time Allocation:** ~10 hours  

✅ **1️⃣ DP Core Techniques**  
   - **Bottom-Up vs Top-Down**  
   - **1D DP: Fibonacci, Coin Change, LIS**  
   - **2D DP: Grid Paths, Knapsack, LCS**  
   - **Bitmask DP**  

✅ **Practice:**  
   - **LeetCode Hard:** DP  
   - **AtCoder DP Contests**  

---

### **📍 Day 6: Mastering Advanced Topics**  
> **Goal:** Understand advanced algorithms for CP.  
⏳ **Time Allocation:** ~10 hours  

✅ **1️⃣ Number Theory & Combinatorics**  
   - **Sieve of Eratosthenes (Prime Numbers in O(N log log N))**  
   - **Modular Inverse (Fermat’s Theorem, Extended Euclidean Algorithm)**  
   - **Fast Exponentiation (O(log N))**  

✅ **2️⃣ String Algorithms (Advanced)**  
   - **Suffix Array & LCP**  
   - **Aho-Corasick Algorithm**  

✅ **3️⃣ Advanced Data Structures**  
   - **Sparse Table (Range Queries O(1))**  
   - **Segment Tree + Lazy Propagation**  
   - **Heavy Light Decomposition (HLD)**  

✅ **Practice:**  
   - **LeetCode Hard:** Advanced Topics  
   - **Codeforces & AtCoder**

---

### **📍 Day 7: Practice, Revision & Speed Optimization**  
> **Goal:** Apply concepts & increase problem-solving speed.  
⏳ **Time Allocation:** ~10 hours  

✅ **1️⃣ Contest Simulations**  
   - Solve **5 Codeforces Div 2/3 contests under timed conditions**  
   - Do **1-hour LeetCode speed runs (5 problems/hour)**  

✅ **2️⃣ Fix Weak Areas & Review Mistakes**  
   - Review **incorrect problems** and debug  
   - Reimplement the hardest problems **from memory**  

✅ **3️⃣ Competitive Programming Speed Optimization**  
   - Fast Input/Output (`scanf/printf`, `ios::sync_with_stdio(false)`)  
   - Debugging tricks (`cerr`, `assert`)  

---

## 🎯 **Final Notes**
- This plan is **brutal**, but after this week, **LeetCode will feel like child's play.**
- **Consistency matters**—practice daily beyond this week.
- **Focus on problem-solving speed & pattern recognition.**

🔥 **Now, GO CRUSH IT.** 🚀





---
---
---






### What is STL?

**STL (Standard Template Library)** is a powerful library in C++ that provides pre-built data structures and algorithms, making coding **faster, more efficient, and less error-prone** in competitive programming (CP) and DSA.

---

## **📌 Components of STL**
STL is divided into **four** main parts:  

1. **Algorithms** → Sorting, Searching, Binary Search, etc.  
2. **Containers** → Data structures like vectors, sets, maps, queues, etc.  
3. **Iterators** → Used to traverse through containers.  
4. **Functions** → Comparators, function objects (functors).  

---

## **📍 1. Algorithms in STL**
STL provides **predefined functions** for commonly used algorithms.  

✅ **Sorting**  
```cpp
sort(arr, arr + n);  // Sorts an array in O(N log N)
sort(v.begin(), v.end());  // Sorts a vector
```

✅ **Searching**  
```cpp
binary_search(v.begin(), v.end(), x);  // Returns true if x exists
auto it = find(v.begin(), v.end(), x); // Returns iterator to x
```

✅ **Min/Max & Swapping**  
```cpp
min(a, b);  
max(a, b);
swap(a, b);
```

✅ **Reversing & Permutations**  
```cpp
reverse(v.begin(), v.end());  
next_permutation(v.begin(), v.end());  
```

---

## **📍 2. Containers (Data Structures in STL)**
Containers are pre-built data structures in STL.

### **📌 Sequence Containers (Linear DS)**
🔹 **Vector** (Dynamic array)  
```cpp
vector<int> v = {1, 2, 3};
v.push_back(4);  // Add element
v.pop_back();    // Remove last element
```

🔹 **Deque** (Double-ended queue)  
```cpp
deque<int> dq;
dq.push_front(1);
dq.push_back(2);
dq.pop_front();
dq.pop_back();
```

🔹 **List (Doubly Linked List)**  
```cpp
list<int> l;
l.push_front(1);
l.push_back(2);
l.pop_front();
```

---

### **📌 Associative Containers (Non-Linear DS)**
🔹 **Set** (Stores unique elements in sorted order)  
```cpp
set<int> s;
s.insert(3);
s.insert(1);
s.insert(2);  // {1,2,3} automatically sorted
```

🔹 **Unordered Set** (Stores unique elements in **random order**)  
```cpp
unordered_set<int> us = {5, 2, 8};
```

🔹 **Map** (Stores key-value pairs in sorted order)  
```cpp
map<int, string> m;
m[1] = "Hello";
m[2] = "World";
```

🔹 **Unordered Map** (Key-value pairs in **random order**)  
```cpp
unordered_map<int, string> um;
```

🔹 **Multiset & Multimap** (Allow duplicate elements)  
```cpp
multiset<int> ms = {1, 1, 2, 2, 3};  // Sorted duplicates
```

---

### **📌 Container Adapters (Specialized Data Structures)**
🔹 **Stack** (LIFO - Last In First Out)  
```cpp
stack<int> s;
s.push(1);
s.push(2);
s.pop();
```

🔹 **Queue** (FIFO - First In First Out)  
```cpp
queue<int> q;
q.push(1);
q.push(2);
q.pop();
```

🔹 **Priority Queue (Max Heap by default)**  
```cpp
priority_queue<int> pq;  // Max Heap
pq.push(5);
pq.push(1);
pq.push(10);  // Top is 10
```

🔹 **Min Heap (Using priority_queue)**  
```cpp
priority_queue<int, vector<int>, greater<int>> minHeap;
```

---

## **📍 3. Iterators (Access Elements Efficiently)**
Iterators are like pointers that allow easy traversal through containers.

```cpp
vector<int> v = {1, 2, 3, 4};
vector<int>::iterator it = v.begin();
cout << *it;  // Prints first element
```

Shorter version using **auto**:  
```cpp
for (auto it = v.begin(); it != v.end(); it++)
    cout << *it << " ";
```

---

## **📍 4. Functions & Functors**
🔹 **Lambda Functions in STL**  
```cpp
sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
```

🔹 **Comparators for Custom Sorting**  
```cpp
bool cmp(int a, int b) {
    return a > b; // Sort in descending order
}
sort(v.begin(), v.end(), cmp);
```

---

## **🔥 Why is STL Important in CP/DSA?**
- Saves time ⏳ (pre-built implementations)
- Optimized 🚀 (uses efficient algorithms internally)
- **Competitive Edge in CP** 💪

🔥 **Mastering STL will make you 2x faster in CP & LeetCode.**
