# 🚀 Dev Internship Survival Guide: Big Tech Edition

A pragmatic, fluff-free roadmap to cracking software engineering internship interviews at top tech companies. Focuses entirely on actionable steps, technical preparation, and data structures.

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

### Pick the language you know best

Interviewers evaluate **your problem-solving skills**, not your favorite programming language.

Your language should help you think clearly and implement solutions quickly—not slow you down because you're fighting syntax.

### If you have multiple options, choose Python

If you're equally comfortable with several languages, **Python is the recommendation**.

**Why Python?**
- ~30% less verbose than Java/C++ — you save precious minutes in OAs[reference:0]
- Built-in data structures (`dict`, `set`, `deque`, `heapq`) solve many problems in 1-2 lines
- Syntax reads like pseudocode — less mental overhead during interviews
- No integer overflow/underflow to worry about

### Don't switch languages before interviews

A common mistake is learning a new language weeks before interviews. Don't. Interview stress is already high enough — you don't want to waste mental energy remembering syntax.

</details>

<details>
<summary><b>📝 Online Assessment (OA) — What to Expect</b></summary>

For most companies, the OA is the first technical screening:

- **2–4 coding problems**
- **60–90 minutes**
- Difficulty increases throughout — the last question is often significantly harder

### Don't expect to finish everything

The OA exists to reduce thousands of applicants to a smaller interview pool. **A perfect score is rarely required.**

**Time management strategy:**
- Solve easier questions first
- Pass as many test cases as possible
- Skip a problem temporarily if stuck — return later if time allows
- A strong partial submission > leaving multiple questions blank

</details>

<details>
<summary><b>📌 Final Advice Before You Start</b></summary>

Don't optimize your preparation for passing OAs. Optimize it for becoming genuinely good at solving unseen problems.

Strong fundamentals in data structures, algorithms, and pattern recognition remain valuable regardless of the company or interview format.

</details>

---

## 2. Data Structures & Algorithms (DSA) Foundations

<details>
<summary><b>📌 Core Topics to Master Before Grinding</b></summary>

Do not jump straight into LeetCode without knowing the theoretical foundations. Master the patterns first — the problems will follow[reference:1].

</details>

### Practice Distribution

For each topic, aim for **3 Easy → 6 Medium → 1 Hard**. This builds confidence, reinforces patterns, and exposes you to enough variation without burnout[reference:2].

---

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

**Core concepts:** O(1) lookups, frequency counting, prefix sums, set operations[reference:3].

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

**Core concepts:** Optimizing O(N²) brute-force to O(N). Two-pointers traverse from ends; sliding window expands/contracts dynamically[reference:4][reference:5].

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

**Core concepts:** Pointer manipulation, in-place reversal, Floyd's cycle detection, fast/slow pointer technique[reference:6].

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

<details>
<summary><b>📚 Curated Problem Lists & Tracking</b></summary>

### Recommended Lists

| List | Problems | Best For | Link |
|------|----------|----------|------|
| **Neetcode 150** | 150 problems, 18 categories | Comprehensive coverage + video explanations for every problem | [neetcode.io/practice](https://neetcode.io/practice) |
| **Blind 75** | 75 essential problems | Quick, focused prep for tight timelines | [leetcode.com/list/oizxjoit](https://leetcode.com/list/oizxjoit) |
| **Grind 75** | 75-169 customizable | Flexible scheduling by available study time | [techinterviewhandbook.org/grind75](https://techinterviewhandbook.org/grind75) |
| **LeetCode 75** | 75 study plan | Official structured learning path from LeetCode | [leetcode.com/studyplan/leetcode-75](https://leetcode.com/studyplan/leetcode-75) |

---

### Progress Tracker Setup

Create a tracker (Notion, Google Sheets, or Excel) with these columns:

| Column | Purpose |
|--------|---------|
| Problem Name | Title + LeetCode number |
| Topic | Arrays, DP, Trees, etc. |
| Difficulty | Easy / Medium / Hard |
| Status | To Do / In Progress / Solved / Revised |
| Date Solved | Track consistency |
| Solution Approach | 1-2 sentences on your intuition |
| Time Complexity | Big-O analysis |
| Space Complexity | Big-O analysis |
| Key Takeaway | Pattern learned or mistake to avoid |
| Re-solved? | Checkbox for spaced repetition (review every 2-4 weeks) |

</details>

---

## 3. The LeetCode Strategy & Coding Patterns

<details>
<summary><b>🎯 How to Practice Efficiently</b></summary>

### The Core Principle: Patterns, Not Problems

> *"I solved 400+ LeetCode problems consistently. Still got stuck in interviews midway. Why? Because I didn't study patterns, I studied just problems."*[reference:12]

LeetCode isn't about memorizing 500 solutions. It's about mastering **~14 patterns** deeply[reference:13]. Once you do that, most problems will feel familiar[reference:14].

### The 14 Essential Patterns

| Pattern | When to Use | Example Problems |
|---------|-------------|------------------|
| **Sliding Window** | Subarrays/substrings, contiguous, min/max in range[reference:15] | Longest Substring Without Repeating, Max Consecutive Ones III |
| **Two Pointers** | Sorted arrays, inward movement, pair sums[reference:16] | Two Sum II, Container With Most Water, 3Sum |
| **Fast & Slow Pointers** | Cycle detection, middle of list[reference:17] | Linked List Cycle, Middle of Linked List |
| **Merge Intervals** | Overlapping intervals | Merge Intervals, Insert Interval |
| **Cyclic Sort** | Missing numbers in range 1-N | Find All Duplicates, First Missing Positive |
| **Tree Traversal (DFS/BFS)** | Trees, grids, path finding[reference:18] | Number of Islands, Binary Tree Level Order |
| **Trie** | Prefix matching, autocomplete | Implement Trie, Word Search II |
| **Heap / Priority Queue** | Top-K elements, scheduling[reference:19] | Top K Frequent, Merge K Sorted Lists |
| **Backtracking** | Combinations, permutations, subsets[reference:20] | Subsets, Permutations, N-Queens |
| **Dynamic Programming** | Overlapping subproblems, optimal substructure | Coin Change, Longest Increasing Subsequence |
| **Binary Search** | Sorted arrays, search in O(log n) | Search in Rotated Sorted Array |
| **Bit Manipulation** | XOR, bit operations | Single Number, Counting Bits |
| **Topological Sort** | Dependency graphs, course schedules | Course Schedule, Alien Dictionary |
| **Monotonic Stack** | Next greater/smaller element | Daily Temperatures, Largest Rectangle |

### The 30-Minute Rule

Try to solve a problem on your own for **30 minutes**[reference:21]. If stuck:

1. Look at the solution/discussion
2. **Understand the pattern** — not just the code
3. Close it and rewrite the code yourself from scratch
4. This builds **active recall**, not passive recognition

> ⚠️ **The "Tutorial Fallacy"**: Watching a Neetcode video, nodding your head, and typing out his solution teaches you nothing[reference:22]. You learned how to watch someone else solve a problem, not how to solve it yourself.

### The 70-20-10 Rule

Spend your practice time on[reference:23][reference:24]:
- **70%** on Medium problems
- **20%** on Hard problems
- **10%** on Easy problems

### Weekly Study Plan (12 Weeks)

| Week | Focus |
|------|-------|
| 1-2 | Arrays & Hashing + Two Pointers |
| 3-4 | Sliding Window + Stack + Binary Search |
| 5-6 | Linked Lists + Trees (DFS/BFS) |
| 7-8 | Graphs + Heaps |
| 9-10 | Dynamic Programming (1D → 2D) |
| 11-12 | Backtracking + Mixed Review + Mocks |

</details>

---

## 4. Essential Communication & Behavioral Cheat Sheet

<details>
<summary><b>🗣️ Interview Day Mechanics (Do Not Skip)</b></summary>

Technical perfection is useless if you cannot communicate.

### Think Out Loud

Never stay silent for more than **30 seconds**. Explain:
- Your thought process
- Trade-offs you're considering
- Why you're choosing a particular data structure
- Edge cases you're thinking about

### Clarify the Problem

Before writing a single line of code:
- Ask about edge cases (empty inputs, negative numbers, size constraints)
- Confirm input/output formats
- Clarify constraints (time/space)

### When You Get Stuck

It's OK to ask for a hint. Interviewers **want** to see how you respond to guidance.

Say something like: *"I'm considering X approach, but I'm not sure about Y. Could you give me a small hint?"*

### Behavioral (STAR Method)

Prepare 3-4 stories using **STAR**:
- **S**ituation: What was the context?
- **T**ask: What was the challenge?
- **A**ction: What did *you* do? (Focus on YOUR contribution)
- **R**esult: What was the quantifiable outcome?

</details>

---

## 5. Curated Resources & Study Materials

<details>
<summary><b>📖 Top Links & Books</b></summary>

### Platforms

| Resource | Link | Best For |
|----------|------|----------|
| **LeetCode** | [leetcode.com](https://leetcode.com) | Practice problems + mocks |
| **Neetcode** | [neetcode.io](https://neetcode.io) | Structured roadmap + video explanations[reference:25] |
| **Tech Interview Handbook** | [techinterviewhandbook.org](https://techinterviewhandbook.org) | Complete prep guide |
| **Pramp** | [pramp.com](https://pramp.com) | Free mock interviews |

### Books

| Book | Why |
|------|-----|
| **Cracking the Coding Interview** (Gayle Laakmann McDowell) | Classic — covers fundamentals and interview mechanics[reference:26] |
| **Elements of Programming Interviews** | More advanced — great for FAANG prep |

### YouTube Channels

| Channel | Best For |
|---------|----------|
| **Neetcode** | Visual explanations of LeetCode problems[reference:27] |
| **Take U Forward** | DSA fundamentals[reference:28] |

### Cheat Sheets

Create your **personal cheat sheet** with[reference:29]:
- Patterns + when to use them
- Go-to code snippets for each data structure
- Top 10 problems per pattern for last-minute revision

</details>

---

**Thanks for reading! :)**
