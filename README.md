# 🚀 Dev Internship Survival Guide: Big Tech Edition

Hi! I'm glad you found this repository :)

I created this guide to help students and aspiring software engineers preparing for internships at Big Tech companies. When I started this journey, I spent countless hours jumping between YouTube videos, blog posts, Reddit threads, and interview experiences, trying to figure out what actually mattered.

This repository is my attempt to bring those lessons together in one place.

Here you'll find the resources, study strategies, interview tips, and preparation methods that helped me land a Big Tech internship, along with many of the things I wish someone had told me when I was getting started.

This isn't meant to be a complete roadmap, there are already plenty of excellent ones out there. Instead, think of it as a practical companion: a collection of actionable advice, useful references, and study materials that can help you prepare more efficiently.

At the end of this guide, I've also included the books, YouTube channels, websites, and other resources that were the most valuable throughout my preparation.

I hope you find something here that makes your own journey a little easier. Good luck, and happy studying!

---

## 📋 Table of Contents
1. [Prerequisites & Language Choice](#1-prerequisites--language-choice)
2. [Data Structures & Algorithms (DSA) Foundations](#2-data-structures--algorithms-dsa-foundations)
3. [The LeetCode Strategy & Coding Patterns](#3-the-leetcode-strategy--coding-patterns)
4. [Essential Communication & Behavioral Cheat Sheet](#4-essential-communication--behavioral-cheat-sheet)
5. [Curated Resources & Study Materials](#5-curated-resources--study-materials)

---

## 1. Prerequisites & Language Choice

<details>
<summary><b>🎯 Choosing Your Programming Language</b></summary>

### Verify the accepted languages first

Before investing time preparing for technical interviews, verify which programming languages are accepted. Check the interview guidelines or ask your recruiter directly.

Most companies support several mainstream languages (e.g., Python, Java, C++, JavaScript, Go), but requirements may vary by company, team, or interview platform.

Always confirm this beforehand rather than relying on assumptions.

**My mistake:** I prepared everything in C# and assumed it would be accepted everywhere. I ended up learning Java in about a month before my interview. Luckily, the syntax was quite similar, but I could have avoided the unnecessary stress by checking beforehand. 😅

---

### Choose the language you know best

Technical interviews are designed to evaluate your ability to analyze problems, design algorithms, select appropriate data structures, reason about trade-offs, and communicate your thinking.

Your programming language is simply the medium through which those skills are expressed.

The best language is therefore the one that allows you to translate ideas into correct, efficient code with the lowest possible cognitive overhead. Mental effort spent recalling syntax, language-specific APIs, or compiler errors is effort that cannot be spent reasoning about the algorithm itself.

From the perspective of **Cognitive Load Theory**, reducing unnecessary cognitive load allows more working memory to be allocated to solving the actual problem.

---

### Don't switch languages right before interviews

A common mistake is learning a new language a few weeks before interviews simply because the target company uses it internally.

In reality, this rarely improves interview performance.

Interviewers typically care far more about whether you can:

- identify the appropriate algorithmic pattern;
- justify your choice of data structures;
- analyze time and space complexity;
- discuss design trade-offs;
- communicate your reasoning clearly;
- produce correct and maintainable code.

A well-structured solution written confidently in a familiar language is almost always preferable to struggling with syntax in a language you recently learned.

---

### If you can freely choose, Python is usually the most practical option

If you are equally comfortable with multiple languages, **Python is generally the most efficient choice** for coding interviews.

Its concise syntax reduces boilerplate and allows you to express algorithms with fewer lines of code, leaving more time for reasoning, testing edge cases, and communicating your approach.

Some advantages include:

- concise and expressive syntax;
- powerful built-in data structures (`list`, `dict`, `set`, `deque`, `heapq`, `Counter`, etc.);
- rapid implementation with minimal boilerplate;
- code that closely resembles pseudocode, improving readability during interviews.

Since interview time is limited, reducing implementation overhead often translates into more time available for algorithmic reasoning.

---

### Concise syntax does **not** replace fundamental understanding

Although Python provides many powerful built-in abstractions, interviewers expect you to understand **what happens beneath those abstractions**.

Using `dict`, `set`, `sort()`, `heapq`, `deque`, or any other standard library component should never be based on memorization alone.

You should be able to explain:

- why a particular data structure is appropriate;
- its average and worst-case time complexity;
- its space complexity;
- the underlying algorithm or data structure at a high level (e.g., hash tables, binary heaps, dynamic arrays);
- the trade-offs compared to alternative approaches.

For example, knowing that dictionary lookups are *typically* **O(1)** is not sufficient. You should also understand that this performance relies on a hash table implementation, why collisions occur, how they affect complexity, and why the worst case can degrade to **O(n)**.

Likewise, calling `sort()` should be accompanied by an understanding that Python uses **Timsort**, a stable comparison-based sorting algorithm with **O(n log n)** worst-case complexity that performs particularly well on partially ordered data.

The goal is not to memorize implementation details from CPython, but to understand the computational principles behind the abstractions you use.

Strong interview performance comes from demonstrating algorithmic reasoning—not from relying on language features as black boxes.

</details>

<details>
<summary><b>📝 Online Assessment (OA) — What to Expect</b></summary>

For most companies, the OA is the first technical screening:

- **2–4 coding problems**
- **60–90 minutes**
- Difficulty increases throughout

### Don't expect to finish everything

The OA exists to reduce thousands of applicants to a smaller interview pool. **A perfect score is rarely required.**

**Time management strategy:**
- Solve easier questions first
- Pass as many test cases as possible
- Skip a problem temporarily if stuck — return later if time allows
- A strong partial submission > leaving multiple questions blank

</details>

---

## 2. Data Structures & Algorithms (DSA) Foundations

<details>
<summary><b>🧠 Core Topics to Master Before Grinding</b></summary>

Don't jump straight into solving hundreds of LeetCode problems without understanding the fundamentals first.

A strong interview preparation process is not simply:

**learn → solve → move on**

A better loop is:

**learn → implement → solve → explain → review → re-solve**

Before heavily relying on problem-solving platforms, make sure you understand the fundamental data structures, algorithms, and complexity concepts that repeatedly appear in technical interviews.

### Data Structures

You should understand what each structure is, how it works, when to use it, and its fundamental time/space trade-offs.

* **Arrays**

  * Static vs. dynamic arrays
  * 1D and 2D arrays
  * Indexing and traversal
  * Insertion/deletion trade-offs

* **Linked Lists**

  * Singly linked lists
  * Doubly linked lists
  * Pointer manipulation
  * Fast/slow pointers

* **Stacks**

  * LIFO
  * Common applications
  * Monotonic stacks

* **Queues**

  * FIFO
  * Deques
  * BFS applications

* **Hash Tables / Sets**

  * Hashing
  * Key-value lookup
  * Frequency counting
  * Collision concept
  * Average vs. worst-case complexity

* **Trees**

  * Binary trees
  * Binary Search Trees
  * Tree traversals
  * Recursion

* **Tries**

  * Prefix-based lookup
  * Autocomplete and dictionary problems

* **Heaps / Priority Queues**

  * Min-heaps
  * Max-heaps
  * Top-K problems
  * Scheduling

* **Graphs**

  * Adjacency lists
  * Adjacency matrices
  * Directed vs. undirected graphs
  * Weighted vs. unweighted graphs

### Algorithms

At minimum, become comfortable with:

* Sorting
* Binary Search
* Recursion
* Greedy algorithms
* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* Tree traversals:

  * Pre-order
  * In-order
  * Post-order
* Dijkstra's algorithm
* Topological Sort
* Disjoint Set Union (Union-Find)
* Dynamic Programming

### Common Problem-Solving Techniques

You should also recognize the following patterns:

* Two Pointers
* Sliding Window
* Fast & Slow Pointers
* Monotonic Stack
* Two Heaps
* Prefix Sum
* Backtracking
* Binary Search on the answer

### Complexity Analysis

Before moving heavily into problem-solving, make sure you can reason about:

* Time complexity
* Space complexity
* Best, average, and worst cases
* Amortized complexity
* Trade-offs between different approaches

You don't need to memorize every implementation detail.

You **do** need to understand why a particular data structure or algorithm is appropriate for a problem.

### Learn the Fundamentals — Then Start Practicing

One important principle is that studying theory should quickly lead into practice.

You do not need to completely "finish learning DSA" before solving problems.

A more effective loop is:

1. Learn the basic concept.
2. Solve a few representative problems.
3. Identify what you don't understand.
4. Return to the theory when necessary.
5. Practice again.

In other words:

> **Don't wait until you feel completely prepared to start practicing. Practice is part of how you become prepared.**

</details>

</details>

<details>
<summary><b>📊 Arrays & Hashing</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Two Sum | [leetcode.com/problems/two-sum](https://leetcode.com/problems/two-sum) |
| Easy | Contains Duplicate | [leetcode.com/problems/contains-duplicate](https://leetcode.com/problems/contains-duplicate) |
| Easy | Valid Anagram | [leetcode.com/problems/valid-anagram](https://leetcode.com/problems/valid-anagram) |
| Medium | Group Anagrams | [leetcode.com/problems/group-anagrams](https://leetcode.com/problems/group-anagrams) |
| Medium | Top K Frequent Elements | [leetcode.com/problems/top-k-frequent-elements](https://leetcode.com/problems/top-k-frequent-elements) |
| Medium | Product of Array Except Self | [leetcode.com/problems/product-of-array-except-self](https://leetcode.com/problems/product-of-array-except-self) |
| Medium | Subarray Sum Equals K | [leetcode.com/problems/subarray-sum-equals-k](https://leetcode.com/problems/subarray-sum-equals-k) |
| Medium | 3Sum | [leetcode.com/problems/3sum](https://leetcode.com/problems/3sum) |
| Medium | Longest Consecutive Sequence | [leetcode.com/problems/longest-consecutive-sequence](https://leetcode.com/problems/longest-consecutive-sequence) |
| Hard | First Missing Positive | [leetcode.com/problems/first-missing-positive](https://leetcode.com/problems/first-missing-positive) |

**Core concepts:** O(1) lookups, frequency counting, prefix sums, set operations.

</details>

---

<details>
<summary><b>↔️ Two Pointers & Sliding Window</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Valid Palindrome | [leetcode.com/problems/valid-palindrome](https://leetcode.com/problems/valid-palindrome) |
| Easy | Remove Duplicates from Sorted Array | [leetcode.com/problems/remove-duplicates-from-sorted-array](https://leetcode.com/problems/remove-duplicates-from-sorted-array) |
| Easy | Two Sum II (Sorted Array) | [leetcode.com/problems/two-sum-ii-input-array-is-sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) |
| Medium | Container With Most Water | [leetcode.com/problems/container-with-most-water](https://leetcode.com/problems/container-with-most-water) |
| Medium | Longest Substring Without Repeating Characters | [leetcode.com/problems/longest-substring-without-repeating-characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) |
| Medium | Max Consecutive Ones III | [leetcode.com/problems/max-consecutive-ones-iii](https://leetcode.com/problems/max-consecutive-ones-iii) |
| Medium | Minimum Size Subarray Sum | [leetcode.com/problems/minimum-size-subarray-sum](https://leetcode.com/problems/minimum-size-subarray-sum) |
| Medium | Longest Repeating Character Replacement | [leetcode.com/problems/longest-repeating-character-replacement](https://leetcode.com/problems/longest-repeating-character-replacement) |
| Medium | Fruit Into Baskets | [leetcode.com/problems/fruit-into-baskets](https://leetcode.com/problems/fruit-into-baskets) |
| Hard | Trapping Rain Water | [leetcode.com/problems/trapping-rain-water](https://leetcode.com/problems/trapping-rain-water) |

**Core concepts:** Optimizing O(N²) brute-force to O(N). Two-pointers traverse from ends; sliding window expands/contracts dynamically.

</details>

---

<details>
<summary><b>🔗 Linked Lists</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Reverse Linked List | [leetcode.com/problems/reverse-linked-list](https://leetcode.com/problems/reverse-linked-list) |
| Easy | Middle of the Linked List | [leetcode.com/problems/middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list) |
| Easy | Linked List Cycle | [leetcode.com/problems/linked-list-cycle](https://leetcode.com/problems/linked-list-cycle) |
| Medium | Remove Nth Node From End | [leetcode.com/problems/remove-nth-node-from-end-of-list](https://leetcode.com/problems/remove-nth-node-from-end-of-list) |
| Medium | Merge Two Sorted Lists | [leetcode.com/problems/merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists) |
| Medium | Add Two Numbers | [leetcode.com/problems/add-two-numbers](https://leetcode.com/problems/add-two-numbers) |
| Medium | Palindrome Linked List | [leetcode.com/problems/palindrome-linked-list](https://leetcode.com/problems/palindrome-linked-list) |
| Medium | Copy List with Random Pointer | [leetcode.com/problems/copy-list-with-random-pointer](https://leetcode.com/problems/copy-list-with-random-pointer) |
| Medium | Reorder List | [leetcode.com/problems/reorder-list](https://leetcode.com/problems/reorder-list) |
| Hard | Reverse Nodes in k-Group | [leetcode.com/problems/reverse-nodes-in-k-group](https://leetcode.com/problems/reverse-nodes-in-k-group) |

**Core concepts:** Pointer manipulation, in-place reversal, Floyd's cycle detection, fast/slow pointer technique.

</details>

---

<details>
<summary><b>🌳 Trees & Graphs</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Invert Binary Tree | [leetcode.com/problems/invert-binary-tree](https://leetcode.com/problems/invert-binary-tree) |
| Easy | Maximum Depth of Binary Tree | [leetcode.com/problems/maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree) |
| Easy | Same Tree | [leetcode.com/problems/same-tree](https://leetcode.com/problems/same-tree) |
| Medium | Validate Binary Search Tree | [leetcode.com/problems/validate-binary-search-tree](https://leetcode.com/problems/validate-binary-search-tree) |
| Medium | Binary Tree Level Order Traversal | [leetcode.com/problems/binary-tree-level-order-traversal](https://leetcode.com/problems/binary-tree-level-order-traversal) |
| Medium | Number of Islands | [leetcode.com/problems/number-of-islands](https://leetcode.com/problems/number-of-islands) |
| Medium | Clone Graph | [leetcode.com/problems/clone-graph](https://leetcode.com/problems/clone-graph) |
| Medium | Course Schedule | [leetcode.com/problems/course-schedule](https://leetcode.com/problems/course-schedule) |
| Medium | Lowest Common Ancestor | [leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree) |
| Hard | Binary Tree Maximum Path Sum | [leetcode.com/problems/binary-tree-maximum-path-sum](https://leetcode.com/problems/binary-tree-maximum-path-sum) |

**Core concepts:** BFS vs. DFS, recursion, tree traversals (in/pre/post-order), cycle detection in graphs (visited states).

</details>

---

<details>
<summary><b>⛰️ Heaps / Priority Queues</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Kth Largest Element in a Stream | [leetcode.com/problems/kth-largest-element-in-a-stream](https://leetcode.com/problems/kth-largest-element-in-a-stream) |
| Easy | Last Stone Weight | [leetcode.com/problems/last-stone-weight](https://leetcode.com/problems/last-stone-weight) |
| Easy | Maximum Product of Two Elements | [leetcode.com/problems/maximum-product-of-two-elements-in-an-array](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array) |
| Medium | K Closest Points to Origin | [leetcode.com/problems/k-closest-points-to-origin](https://leetcode.com/problems/k-closest-points-to-origin) |
| Medium | Merge k Sorted Lists | [leetcode.com/problems/merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists) |
| Medium | Task Scheduler | [leetcode.com/problems/task-scheduler](https://leetcode.com/problems/task-scheduler) |
| Medium | Reorganize String | [leetcode.com/problems/reorganize-string](https://leetcode.com/problems/reorganize-string) |
| Medium | Find Median from Data Stream | [leetcode.com/problems/find-median-from-data-stream](https://leetcode.com/problems/find-median-from-data-stream) |
| Medium | Kth Largest Element in an Array | [leetcode.com/problems/kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array) |
| Hard | Sliding Window Maximum | [leetcode.com/problems/sliding-window-maximum](https://leetcode.com/problems/sliding-window-maximum) |

**Core concepts:** Top-K elements, dynamic median, task scheduling. Min-heap for kth largest; max-heap for kth smallest.

</details>

---

<details>
<summary><b>🧩 Dynamic Programming</b></summary>

| Difficulty | Problem | Link |
|------------|---------|------|
| Easy | Climbing Stairs | [leetcode.com/problems/climbing-stairs](https://leetcode.com/problems/climbing-stairs) |
| Easy | House Robber | [leetcode.com/problems/house-robber](https://leetcode.com/problems/house-robber) |
| Easy | Best Time to Buy and Sell Stock | [leetcode.com/problems/best-time-to-buy-and-sell-stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock) |
| Medium | Coin Change | [leetcode.com/problems/coin-change](https://leetcode.com/problems/coin-change) |
| Medium | Longest Increasing Subsequence | [leetcode.com/problems/longest-increasing-subsequence](https://leetcode.com/problems/longest-increasing-subsequence) |
| Medium | Word Break | [leetcode.com/problems/word-break](https://leetcode.com/problems/word-break) |
| Medium | House Robber II | [leetcode.com/problems/house-robber-ii](https://leetcode.com/problems/house-robber-ii) |
| Medium | Palindromic Substrings | [leetcode.com/problems/palindromic-substrings](https://leetcode.com/problems/palindromic-substrings) |
| Medium | Longest Palindromic Substring | [leetcode.com/problems/longest-palindromic-substring](https://leetcode.com/problems/longest-palindromic-substring) |
| Hard | Longest Common Subsequence | [leetcode.com/problems/longest-common-subsequence](https://leetcode.com/problems/longest-common-subsequence) |

**Core concepts:** Memoization (top-down) vs. Tabulation (bottom-up), state definition, transition functions, base cases. Master 1D DP before moving to 2D.

</details>

---

## 3. The LeetCode Strategy & Coding Patterns

<details>
<summary><b>🎯 How to Practice Efficiently</b></summary>

### The Core Principle: Patterns, Not Problems

LeetCode isn't about memorizing 500 solutions... It's about mastering **~14 patterns** deeply. Once you do that, most problems will feel familiar.

### The 14 Essential Patterns

| Pattern | When to Use | Example Problems |
|---------|-------------|------------------|
| **Sliding Window** | Subarrays/substrings, contiguous, min/max in range | Longest Substring Without Repeating, Max Consecutive Ones III |
| **Two Pointers** | Sorted arrays, inward movement, pair sums | Two Sum II, Container With Most Water, 3Sum |
| **Fast & Slow Pointers** | Cycle detection, middle of list | Linked List Cycle, Middle of Linked List |
| **Merge Intervals** | Overlapping intervals | Merge Intervals, Insert Interval |
| **Cyclic Sort** | Missing numbers in range 1-N | Find All Duplicates, First Missing Positive |
| **Tree Traversal (DFS/BFS)** | Trees, grids, path finding | Number of Islands, Binary Tree Level Order |
| **Trie** | Prefix matching, autocomplete | Implement Trie, Word Search II |
| **Heap / Priority Queue** | Top-K elements, scheduling | Top K Frequent, Merge K Sorted Lists |
| **Backtracking** | Combinations, permutations, subsets | Subsets, Permutations, N-Queens |
| **Dynamic Programming** | Overlapping subproblems, optimal substructure | Coin Change, Longest Increasing Subsequence |
| **Binary Search** | Sorted arrays, search in O(log n) | Search in Rotated Sorted Array |
| **Bit Manipulation** | XOR, bit operations | Single Number, Counting Bits |
| **Topological Sort** | Dependency graphs, course schedules | Course Schedule, Alien Dictionary |
| **Monotonic Stack** | Next greater/smaller element | Daily Temperatures, Largest Rectangle |

</details>

<details>
<summary><b>⏱️ Recommended Time Allocation</b></summary>

### Don't struggle forever—but don't give up too early.

A good rule of thumb is to spend **20–30 minutes** reasoning about a problem independently before looking for help. This creates **productive struggle**, a learning strategy shown to improve long-term problem-solving ability compared to immediately reading solutions.

If you're still stuck:

1. Review an editorial or high-quality solution.
2. Focus on the **underlying algorithmic pattern**, not the implementation details.
3. Identify *why* that approach works, including its time and space complexity.
4. Close the solution and implement it again **entirely from memory**.
5. Compare your implementation with the reference and note any gaps in understanding.

The objective is not to reproduce code—it is to internalize the reasoning process so you can transfer the same pattern to unfamiliar problems.

### Recommended Practice Distribution

| Difficulty | Suggested Time |
|------------|---------------:|
| **Medium** | **≈75%** |
| **Easy** | **≈20%** |
| **Hard** | **≈5%** |

This distribution reflects the difficulty of most software engineering interviews. **Medium** problems provide the highest return on investment because they reinforce the algorithmic patterns that appear most frequently during technical interviews. **Easy** problems strengthen fundamentals and improve implementation speed, while **Hard** problems are best used to expand your thinking rather than as the core of your preparation.

</details>

<details>
<summary><b>✍️ Practice Strategy: Quality Over Quantity</b></summary>

Your practice should follow a deliberate process.

### 1. Understand the problem

Before touching the keyboard:

* Read the problem carefully.
* Identify the inputs and outputs.
* Check the constraints.
* Look for ambiguities.
* Think about edge cases.
* Restate the problem in your own words.

### 2. Start with the brute-force solution

Don't immediately search for the "clever" solution.

First ask:

> **What is the simplest correct solution I can think of?**

Write it down mentally, on paper, or in pseudocode.

Then analyze:

* time complexity;
* space complexity;
* bottlenecks.

The brute-force solution gives you a baseline from which you can reason about optimization.

### 3. Optimize deliberately

Ask:

* Where is the bottleneck?
* Am I repeating work?
* Can I trade space for time?
* Would a hash table help?
* Is the input sorted?
* Could two pointers work?
* Could a sliding window work?
* Is this a graph traversal?
* Is there overlapping subproblem structure?
* Can I use a heap?
* Can I binary-search the answer?

Optimization should be a consequence of reasoning, not pattern guessing.

### 4. Spend enough time struggling

A useful rule of thumb is to spend around **20–30 minutes** seriously attempting a problem before consulting an editorial or solution.

If you're completely blocked, don't turn the session into a two-hour staring contest with the same `for` loop.

Instead:

1. Read a hint or editorial.
2. Identify the underlying pattern.
3. Understand why the solution works.
4. Close the solution.
5. Re-implement it from memory.
6. Explain the approach.
7. Revisit the problem later.

The goal is not to reproduce someone else's code.

The goal is to internalize the reasoning well enough to transfer it to a different problem.

### 5. Test manually

Before submitting:

* test the normal case;
* test an empty input;
* test a single element;
* test duplicates;
* test negative values when relevant;
* test zero;
* test very small inputs;
* test very large inputs;
* test boundary conditions.

### 6. Record the lesson

After solving, write down:

* the pattern;
* the key insight;
* the bottleneck;
* the complexity;
* what initially confused you;
* what you would look for next time.

**Quality > quantity.**

The number of problems you solve matters far less than how much problem-solving ability you extract from each one.

</details>


<details>
<summary><b>🧠 Understanding ≠ Learning</b></summary>

One of the easiest traps in technical interview preparation is confusing **recognition with mastery**.

You can watch a video, read an editorial, and feel that everything makes sense — without actually being able to reproduce the reasoning later.

### Understanding

You understand something when you can follow an explanation and recognize why it makes sense.

### Learning

You have learned something when you can **reproduce, explain, and apply the concept independently**, including after some time has passed and in a slightly different problem.

This distinction matters enormously for DSA.

For example:

> "I watched a video about sliding window and everything made sense."

is not the same as:

> "I can recognize when sliding window applies, explain why it works, implement it, analyze its complexity, and adapt it to an unfamiliar problem."

### A practical test

After studying a concept, close the tutorial and ask yourself:

* Can I explain the idea without looking at my notes?
* Can I implement the basic technique from memory?
* Can I explain when it should and should not be used?
* Can I analyze its time and space complexity?
* Can I solve a new problem using it?
* Can I explain the solution to someone else?

If the answer is no, that's not failure.

It simply means the material has moved from **exposure** to **practice** — which is exactly where learning happens.

### Avoid the "perfect resource" trap

You may eventually find a video, book, or course that suddenly makes a topic feel much clearer.

That's useful, but don't assume that the resource itself created the understanding.

Often, understanding improves because you've already encountered the concept several times through different explanations, exercises, mistakes, and applications.

Your knowledge is cumulative.

</details>

<details>
<summary><b>🎯 Focus Before Breadth</b></summary>

A common mistake during DSA preparation is trying to learn too many topics simultaneously.

You open one tab about graphs, another about dynamic programming, another about system design, another about trees — and suddenly you're studying everything while mastering nothing.

### Prefer depth before breadth

When learning a new topic:

1. Learn the fundamental concept.
2. Solve a small number of representative problems.
3. Explain the approach in your own words.
4. Identify gaps in your understanding.
5. Review only what you need.
6. Re-solve problems later.
7. Move to the next topic.

You don't need to master an entire field before moving forward.

But you should avoid constantly switching between unrelated topics simply because another resource looks interesting.

> **One topic understood deeply is usually more valuable than five topics superficially recognized.**

This does not mean your preparation must be rigid. Interleaving and mixed review are useful once you have established a foundation.

The important distinction is:

**exploration is useful; constant context switching is not.**

</details>


<details>
<summary><b>🎯 Mock Interviews: Practice the Real Skill</b></summary>

Solving LeetCode alone is fundamentally different from solving a problem while another person watches, asks questions, challenges your assumptions, and expects you to communicate your reasoning.

That's why mock interviews are essential.

### Start mocks earlier than you think

Don't wait until you believe you're "ready."

Mocks can reveal:

* knowledge gaps;
* communication problems;
* poor time management;
* difficulty thinking aloud;
* difficulty handling follow-up questions;
* anxiety under pressure;
* weak debugging habits.

In other words, mocks are not only a final rehearsal.

**They are a diagnostic tool.**

### What a good mock should simulate

Whenever possible, reproduce the real interview environment:

* use a realistic time limit;
* don't look at solutions;
* communicate your reasoning aloud;
* ask clarifying questions;
* write code while talking;
* test your implementation;
* discuss complexity;
* handle follow-up questions;
* receive feedback afterward.

### Practice unfamiliar problems

Don't only mock yourself with problems you already know.

Whenever possible, use a random problem from a topic you've studied but haven't memorized.

This tests whether you actually understand the pattern rather than whether you recognize a familiar question.

### What to evaluate after every mock

Ask:

| Area                  | Questions                                |
| --------------------- | ---------------------------------------- |
| Problem Understanding | Did I ask enough clarifying questions?   |
| Communication         | Did I explain my reasoning clearly?      |
| Algorithm             | Did I identify an appropriate approach?  |
| Optimization          | Did I recognize the bottleneck?          |
| Coding                | Was my implementation clean and correct? |
| Testing               | Did I test edge cases?                   |
| Complexity            | Could I justify Big-O?                   |
| Time Management       | Did I spend too long on one step?        |
| Adaptability          | How did I react to hints or changes?     |

### Mock frequency

During my own preparation, I practiced mocks regularly.

A useful starting point is **one mock per week**, then adjust the frequency according to your preparation stage and how much feedback you need.

The important thing is consistency, not blindly maximizing the number of mocks.

### Resources

**Pramp** is one option for peer-to-peer mock interviews.

You can also practice with:

* classmates;
* mentors;
* friends;
* colleagues;
* other candidates preparing for interviews.

If possible, practice in English occasionally when applying to international companies.

A mock interview should leave you with a concrete answer to:

> **"What should I practice next?"**

**Source / inspiration:** Leandro Moreira, *Preparação para Entrevistas de Programação*.

</details>



<details>
<summary><b>🗓️ Weekly Study Plan (12 Months)</b></summary>

### How to Use This Roadmap

This roadmap is a **framework, not a deadline**.

The amount of time required for each topic depends on:

* your previous programming experience;
* your DSA background;
* your available study time;
* how quickly you retain concepts;
* the difficulty of the problems you encounter.

If a topic takes longer than expected, that is not necessarily a problem.

### Use readiness, not the calendar

Before moving on, ask:

* Can I explain the core data structure?
* Can I implement its basic operations?
* Can I recognize common patterns involving it?
* Can I solve representative Easy problems?
* Can I solve at least some Medium problems?
* Can I explain my solution without reading notes?
* Can I analyze time and space complexity?

If the answer is mostly yes, continue.

If not, spend more time practicing.

**The goal is not to finish the roadmap.**

The goal is to become capable of solving unfamiliar problems.

This is why consistency and genuine understanding matter more than maximizing the number of problems completed.


| Weeks | Focus                          |
| ----- | ------------------------------ |
| 1–3   | Arrays & Hashing               |
| 4–5   | Two Pointers                   |
| 6–7   | Sliding Window                 |
| 8–9   | Stack and Queue                |
| 10–12 | Binary Search                  |
| 13–15 | Linked List                    |
| 16–20 | Trees                          |
| 21–22 | Heap / Priority Queue          |
| 23–25 | Backtracking                   |
| 26    | Tries                          |
| 27–31 | Graphs                         |
| 32–33 | Advanced Graphs                |
| 34–37 | 1-D Dynamic Programming        |
| 38–41 | 2-D Dynamic Programming        |
| 42–44 | Greedy                         |
| 45–46 | Intervals                      |
| 47–49 | Math & Geometry                |
| 50–51 | Bit Manipulation               |
| 52    | Mixed Review + Mock Interviews |

**If you're not a CS student:** I strongly recommend taking a Data Structures & Algorithms course at your university if you can. I even attended DSA classes without taking the course for credit because my curriculum didn't allow me to enroll, and it was still extremely valuable. 😂

University courses and coding interviews aren't always taught the same way. Interviews often provide ready-to-use data structures, while university courses may ask you to implement stacks, queues, linked lists, and trees from scratch. Understanding how they work under the hood gave me a much stronger foundation.

**Take your time.** Consistency and genuine understanding are more valuable than rushing through the roadmap or maximizing your problem count.

</details>


<details>
<summary><b>📚 Curated Problem Lists & Tracking</b></summary>

### Recommended Problem Lists

| List             | Best For                                                                                                                                       | Link                                              |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| **Blind 75**     | A great starting point if you're short on time and want to learn the most common interview patterns.                                           | https://neetcode.io/practice/practice/blind75     |
| **NeetCode 150** | A balanced and comprehensive list covering all major DSA topics.                                                                               | https://neetcode.io/practice/practice/neetcode150 |
| **NeetCode 250** | The most complete option. This is the list I personally completed, and I'd highly recommend it if you have enough time before your interviews. | https://neetcode.io/practice/practice/neetcode250 |

> **My recommendation:** If your timeline allows it, go through the **NeetCode 250**. Otherwise, the **NeetCode 150** or **Blind 75** are excellent alternatives depending on how much time you have available.

---

### Progress Tracker & Spaced Repetition

One of the biggest mistakes people make is treating LeetCode as a checklist.

Solving a problem once does not necessarily mean that you learned the underlying pattern.

The goal is not:

> "How many problems have I solved?"

The better question is:

> **"How many patterns can I recognize and reproduce independently?"**

### Use spaced repetition

Don't simply solve a problem and permanently archive it.

Instead, revisit important problems after increasing intervals.

For example:

**Day 0 → Day 3 → Day 7 → Day 14 → Day 30**

When reviewing:

1. Hide the solution.
2. Read only the problem statement.
3. Try to reconstruct the approach.
4. Explain the idea aloud.
5. Implement the solution.
6. Analyze time and space complexity.
7. Compare with your previous approach.
8. Record what you forgot or misunderstood.

The important part is attempting retrieval **before looking at your notes**.

If you can recognize the solution only after seeing it again, you may remember the problem — but you have not necessarily developed transferable problem-solving ability.

### Track more than "Solved"

A useful tracker can contain:

| Column            | Purpose                                 |
| ----------------- | --------------------------------------- |
| Problem Name      | Title + LeetCode number                 |
| Topic             | Arrays, DP, Trees, etc.                 |
| Pattern           | Sliding Window, DFS, Two Pointers, etc. |
| Difficulty        | Easy / Medium / Hard                    |
| Status            | To Do / In Progress / Solved / Revised  |
| Date Solved       | Track consistency                       |
| Solution Approach | 1–2 sentences describing the intuition  |
| Time Complexity   | Big-O analysis                          |
| Space Complexity  | Big-O analysis                          |
| Key Takeaway      | Pattern learned or mistake made         |
| Re-solved?        | Track spaced repetition                 |
| Confidence        | Low / Medium / High                     |

### The real purpose of the tracker

A tracker should help you:

* identify weak topics;
* detect recurring mistakes;
* measure consistency;
* schedule reviews;
* recognize patterns;
* prepare efficiently before interviews.

**Do not optimize for the number of green checkmarks. Optimize for retention and transfer.**

### Recommended Templates & Resources

These are excellent resources created by the community that helped shape my own study process:

| Resource                              | Description                                                                                                                                                                        | Credits                                                                                                              |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **LeetCode Template File**            | A clean template for documenting each problem, your intuition, complexity analysis, and key takeaways. Great for building long-term understanding instead of memorizing solutions. | Mykel B. — https://github.com/mykelbengineer/LeetcodeTemplateFile                                                    |
| **How I Study LeetCode (YouTube)**    | Explains an effective review strategy and why revisiting problems is just as important as solving new ones.                                                                        | https://www.youtube.com/watch?v=Xy2VokU7erM                                                                          |
| **LeetCoding by Ebbinghaus (Notion)** | A Notion template built around the **Ebbinghaus Forgetting Curve**, helping you schedule reviews at increasing intervals to maximize retention.                                    | https://rapid-talon-5e6.notion.site/LeetCoding-by-Ebbinghaus-s-c43eafaf771c4016b8c8f60407eae912                      |
| **LeetCode Tracker (Google Sheets)**  | A spreadsheet for organizing solved problems, review dates, and progress over time.                                                                                                | https://docs.google.com/spreadsheets/d/1EEYzyD_483B-7CmWxsJB_zycdv4Y5dxnzcoEQtaIfuk/edit?gid=329533698#gid=329533698 |
| **LeetCode Study Dashboard (Notion)** | A complete dashboard for organizing your interview preparation, notes, and progress.                                                                                               | https://chartreuse-september-30d.notion.site/home-19e631afd4d74eb98d1152b577065345                                   |

> **Why spaced repetition?** The **Ebbinghaus Forgetting Curve** shows that we naturally forget information over time unless we review it. Revisiting problems after a few days, weeks, and months reinforces the underlying patterns and makes them much easier to recognize during interviews. The objective isn't to memorize solutions—it's to internalize the reasoning behind them so you can solve unseen problems with confidence.

</details>

---

## 4. Essential Communication & Behavioral Cheat Sheet

<details>
<summary><b>🗣️ Interview Day Mechanics — A Step-by-Step Process</b></summary>

Technical interviews are not simply coding tests.

The interviewer is evaluating how you **understand problems, reason about trade-offs, communicate, adapt, and collaborate**.

A strong candidate should therefore treat the interview as a collaborative problem-solving session rather than a silent exam.

### Before Writing Code

#### 1. Listen carefully

Don't start coding immediately.

Make sure you understand:

* what the problem is asking;
* the input format;
* the expected output;
* the constraints;
* what assumptions are allowed;
* whether the problem statement is ambiguous.

If something is unclear, **ask**.

Ambiguity can be intentional: interviewers may want to see whether you notice missing information and ask useful questions.

#### 2. Restate the problem

Explain the problem back in your own words.

For example:

> "So, if I understand correctly, we need to return X given Y, and the input can contain Z. Is that correct?"

This prevents solving the wrong problem.

#### 3. Validate the examples

Don't rely only on the example provided by the interviewer.

Create one or two additional examples.

Include useful edge cases, but don't waste interview time constructing enormous examples.

Walk through them manually.

#### 4. Start with the brute-force approach

Before searching for the optimal solution, describe the simplest correct approach.

Explain:

* how it works;
* its time complexity;
* its space complexity;
* why it may be too slow or expensive.

This gives you a baseline for optimization.

#### 5. Discuss the optimized approach

Now look for bottlenecks.

Explain what you're changing and **why**.

For example:

> "The brute-force approach repeatedly searches the array, which gives us O(n²). If we store previously seen values in a hash table, we can reduce the lookup cost and obtain an O(n) solution."

The important part is not saying "I'll use a hash map."

The important part is explaining **why the data structure changes the complexity**.

#### 6. Walk through the algorithm

Before writing implementation details, use:

* pseudocode;
* a small example;
* a diagram;
* or verbal reasoning.

Then manually execute the algorithm against your examples.

This is a cheap way to catch logical errors before implementation.

---

### While Coding

#### 7. Keep communicating

Don't disappear into silence.

Think out loud:

* explain what you're implementing;
* mention assumptions;
* explain important decisions;
* call out trade-offs;
* verbalize uncertainty when necessary.

You don't need to narrate every character you type.

The goal is to make your reasoning observable.

#### 8. Implement the solution

Use the language you are most comfortable with.

Prefer clarity over cleverness.

Interview code should be:

* correct;
* readable;
* maintainable;
* appropriately simple.

#### 9. Test your implementation

Don't assume that compiling means the solution is correct.

Walk through your code with:

* the original example;
* your own example;
* edge cases;
* boundary conditions.

Look specifically for:

* off-by-one errors;
* incorrect loop bounds;
* missing base cases;
* null/empty inputs;
* duplicate values;
* incorrect pointer movement.

#### 10. Revisit complexity

After implementation, explicitly state:

> **Time:** O(...)

> **Space:** O(...)

Explain where those costs come from.

If you changed the implementation during the interview, update your complexity analysis accordingly.

---

### When You Get Stuck

Getting stuck is normal.

Don't silently struggle until the interview ends.

A better approach is to communicate your current reasoning:

> "I'm considering X because of Y, but I'm not sure how to handle Z. Could you give me a small hint?"

Then incorporate the hint and continue reasoning.

The interviewer is also evaluating **how you respond to new information**.

---

### Treat the Interviewer as a Collaborator

A coding interview is closer to collaborative problem-solving than to an exam.

You should be:

* professional;
* curious;
* receptive to feedback;
* willing to ask questions;
* conscious of time.

Think of the interviewer as a potential teammate who is trying to understand how you work.

</details>

<details>
<summary><b>💭 Rejection Is Part of the Process</b></summary>

One of the least discussed parts of interview preparation is rejection.

You can be technically strong and still fail an interview.

Interviews contain randomness:

* the specific problem you receive;
* your familiarity with the pattern;
* the interviewer;
* communication dynamics;
* time pressure;
* the interviewer's expectations;
* your mental state that day.

A rejection is therefore **not a reliable measurement of your overall intelligence or engineering potential**.

### Don't optimize for never failing

Instead, optimize for:

**learning → practicing → simulating → reviewing → improving**

If an interview goes badly, ask:

* What topic exposed a weakness?
* Did I misunderstand the problem?
* Did I communicate poorly?
* Did I spend too much time on one approach?
* Did I struggle with a particular data structure?
* Did I fail to test edge cases?
* Did I panic when I got stuck?
* What should I practice before the next interview?

Turn the interview into feedback.

### Consistency beats intensity

You don't need to study for six hours every day.

A sustainable schedule that you can maintain for months is often more valuable than an intense schedule that lasts two weeks.

For example:

* 3 sessions/week × 2 hours during long-term preparation;
* 5 sessions/week × 1 hour when an interview is approaching.

These are examples, not universal rules.

The correct schedule depends on your available time, background, and goals.

> **There is no magic "learn DSA in X days" formula.**

Give yourself enough time to make mistakes, revisit concepts, and build genuine intuition.

</details>


---

## 5. Curated Resources & Study Materials

<details>
<summary><b>📖 Top Links & Books</b></summary>

### Targeted Company Questions

Once you have a solid DSA foundation, **targeted practice can make your preparation much more efficient.**

Companies often have recurring topics, patterns, or question styles. Some may reuse questions, while others use variations or completely different problems. It depends heavily on the company, team, role, and interviewer.

What I did:

1. **Completed the NeetCode 250 first** to build a solid foundation.
2. Then, for each company I was targeting, I focused on **recent company-tagged questions I hadn't solved yet**.
3. I prioritized newer questions and recurring patterns rather than trying to memorize exact problems.

This doesn't guarantee that you'll get one of those questions — **there are no guarantees in interviews** — but I found it extremely useful for understanding what to prioritize and becoming familiar with the types of problems a company tends to ask.

You don't necessarily need LeetCode Premium for this. There are several community-maintained GitHub repositories and tools that collect company-wise interview questions, often organized by recency. Reddit can also be useful for finding recent interview experiences and comparing what candidates report.

A few resources I found particularly useful:

* **[LeetCode Company-Wise Interview Questions](https://github.com/snehasishroy/leetcode-companywise-interview-questions)** — company-specific questions organized by recency, difficulty, and frequency.
* **[LeetCode Company Wise Questions](https://github.com/ssavi-ict/LeetCode-Which-Company)** — a free tool/extension for accessing company-specific questions without relying on LeetCode Premium.

**Do your research.** Look into the company's interview format, the topics commonly reported by candidates, and whether they tend to reuse questions or ask variations. If you know people who have interviewed there, asking about their experience can also be valuable — although current employees may understandably be limited in what they can share.

The goal isn't to memorize a company's question bank. **It's to spend your limited preparation time on the problems and patterns most relevant to your target.**


### Platforms

| Resource                    | Link                                                           | Best For                                                     |
| --------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------ |
| **LeetCode**                | [leetcode.com](https://leetcode.com)                           | DSA practice, contests, and interview problems               |
| **NeetCode**                | [neetcode.io](https://neetcode.io)                             | Structured roadmap, patterns, and video explanations         |
| **Tech Interview Handbook** | [techinterviewhandbook.org](https://techinterviewhandbook.org) | Comprehensive interview preparation guide                    |
| Preparação para Entrevistas de Programação| [leandromoreira.com](https://docs.google.com/document/d/1gRL6ILI2XI8_eFGCrr-Q_ZxkdcnzECa-WN0kX0GVIDc/edit?tab=t.0) | Interview preparation, problem-solving process, learning methodology, spaced repetition, and mock interviews |
| **Pramp**                   | [pramp.com](https://www.pramp.com)                             | Free peer-to-peer mock interviews                            |
| **HackerRank**              | [hackerrank.com](https://www.hackerrank.com)                   | Coding practice and interview preparation                    |
| **GeeksforGeeks**           | [geeksforgeeks.org](https://www.geeksforgeeks.org)             | DSA explanations, tutorials, and practice                    |
| **Exercism**                | [exercism.org](https://exercism.org)                           | Improving programming fundamentals and language fluency      |
| **Codeforces**              | [codeforces.com](https://codeforces.com)                       | Competitive programming and problem-solving                  |
| **DSA Tracker**             | [dsatracker.tech](https://www.dsatracker.tech)                 | Progress tracking, curated problem sheets, and study streaks |
| **CodeTrack Pro**           | [GitHub](https://github.com/javydevx/leetcode-tracker)         | LeetCode progress tracking + spaced repetition               |
| **LeetTrackr**              | [GitHub](https://github.com/realsubodh/LeetTrackr)             | LeetCode statistics, progress, and activity tracking         |
| **CodeKaro**                | [codekaro.live](https://codekaro.live)                         | Free peer mock interviews with a shared editor               |

### Books

| Book                                                        | Why                                                                                           |
| ----------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Cracking the Coding Interview** (Gayle Laakmann McDowell) | Classic — covers DSA fundamentals, problem-solving, and interview mechanics                   |
| **Elements of Programming Interviews**                      | More advanced — a large collection of challenging programming problems and interview patterns |
| **Algorithms** (Robert Sedgewick & Kevin Wayne)             | Excellent for building a deeper understanding of algorithms and data structures               |
| **Clean Code** (Robert C. Martin)                           | Practical principles for writing readable, maintainable code                                  |
| **The Pragmatic Programmer** (David Thomas & Andrew Hunt)   | Practical software engineering principles and problem-solving mindset                         |

> **Don't neglect software engineering fundamentals.** Interviews can evaluate OOP, clean code, readability, and engineering judgment even when they're not explicitly asked. Know the principles, but also understand **when to apply them and when they add unnecessary complexity**. In the age of AI-generated code, being able to review, simplify, and improve code is increasingly important.

### YouTube Channels

I used YouTube **a lot** during my preparation. These were some of the channels that helped me most, organized by what I used them for.

#### DSA & Computer Science Fundamentals

| Channel                                                       | Best For                                                                 |
| ------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **[Abdul Bari](https://www.youtube.com/@abdul_bari)**         | Algorithms, data structures, and deeper theoretical understanding        |
| **[CS Dojo](https://www.youtube.com/@CSDojo)**                | DSA, coding interviews, and general software engineering guidance        |
| **[freeCodeCamp.org](https://www.youtube.com/@freecodecamp)** | Full courses, CS fundamentals, programming, and many long-form tutorials |
| **[Bro Code](https://www.youtube.com/@BroCodez)**             | Programming fundamentals and quick language/framework explanations       |
| **[Take U Forward](https://www.youtube.com/@takeUforward)**   | DSA fundamentals and structured problem-solving                          |

#### Coding Practice & Problem Walkthroughs

| Channel                                                | Best For                                                |
| ------------------------------------------------------ | ------------------------------------------------------- |
| **[NeetCode](https://www.youtube.com/@NeetCode)**      | Step-by-step solutions and recognizing problem patterns |
| **[Greg Hogg](https://www.youtube.com/@GregHogg)**     | Coding interview preparation, DSA, and problem-solving  |
| **[Nick White](https://www.youtube.com/@NickWhite)**   | LeetCode walkthroughs and interview problem-solving     |

#### Mock Interviews

| Channel                                                                     | Best For                                                                                |
| --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **[Alpha-Code](https://www.youtube.com/@AlphaCodeCS)** | Coding interview problems and technical preparation     |
| **[Clément Mihailescu](https://www.youtube.com/@clem)**| Coding interviews, interview preparation, and career advice |

#### Behavioral Interviews & Communication

| Channel                                                     | Best For                                                                                      |
| ----------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **[Jeff H Sipe – Practice Interviews](https://www.youtube.com/@JeffHSipe)** | Realistic mock technical interviews and practicing communication while solving problems |
| **[CareerVidz](https://www.youtube.com/@CareerVidz)**       | Behavioral interviews, common interview questions, and answer structure                       |
| **[Life at Google](https://www.youtube.com/@LifeatGoogle)** | Google interview guidance, hiring process, and examples of technical/non-technical interviews |

> **Don't underestimate communication.** In technical interviews, you're not only being evaluated on whether you can solve the problem. How you communicate your approach, clarify requirements, explain trade-offs, respond to feedback, and think out loud can matter significantly.

> **And don't just watch.** It's very easy to spend hours consuming interview content and feel productive without actually improving. Try the problem yourself first, write code, explain your reasoning out loud, and only then use the video to fill the gaps.

#### Industry, Career & Day-in-the-Life Content

I also really enjoyed **“day in the life” and SWE vlog content**, especially from engineers working at large tech companies. This wasn't a study resource in the traditional sense, but it helped me a lot on difficult days. Seeing other people studying, working, and building their careers gave me motivation to keep going when I was tired or discouraged.

Just be careful with this type of content too: **don't turn motivational videos into another form of procrastination.** Use them as inspiration, then go back to studying.

### A note on how to use YouTube

You don't need to watch everything. Pick a few trusted channels, use them when you need an explanation, and **prioritize active practice over passive consumption**.

A good rule is:

**Try → struggle → study → solve → review.**

Not:

**Watch → watch another video → watch a motivational video → somehow it's 2 a.m.** 😅

The goal is not to become very good at watching people solve problems. **The goal is to become good at solving them yourself.**


</details>

---

**Thanks for reading! :)**
