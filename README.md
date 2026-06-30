# 🚀 Dev Internship Survival Guide: Big Tech Edition

Hi! I'm glad you found this repository :)

I created this guide to help students and aspiring software engineers preparing for internships at Big Tech companies. When I started this journey, I spent countless hours jumping between YouTube videos, blog posts, Reddit threads, and interview experiences, trying to figure out what actually mattered.

This repository is my attempt to bring those lessons together in one place.

Here you'll find the resources, study strategies, interview tips, and preparation methods that helped me land a Big Tech internship, along with many of the things I wish someone had told me when I was getting started.

This isn't meant to be a complete roadmap, there are already plenty of excellent ones out there. Instead, think of it as a practical companion: a collection of actionable advice, useful references, and study materials that can help you prepare more efficiently.

At the end of this guide, I've also included the books, YouTube channels, websites, and other resources that were the most valuable throughout my preparation.

**Don't optimize your preparation for passing OAs. Optimize it for becoming genuinely good at solving unseen problems.** Strong fundamentals in data structures, algorithms, and pattern recognition remain valuable regardless of the company or interview format.

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

### Pick the language you know best

Interviewers evaluate **your problem-solving skills**, not your favorite programming language.

Your language should help you think clearly and implement solutions quickly, not slow you down because you're fighting syntax.

### If you have multiple options, choose Python

If you're equally comfortable with several languages, **Python is the recommendation.**

**Why Python?**
- Less verbose
- Built-in data structures
- Syntax reads like pseudocode

### Don't switch languages before interviews

A common mistake is learning a new language weeks before interviews. Don't. Interview stress is already high enough — you don't want to waste mental energy remembering syntax.

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
<summary><b>Core Topics to Master Before Grinding</b></summary>

Don't jump straight into solving LeetCode problems without understanding the fundamentals first.
What worked well for me was keeping each week focused on a single topic. I would spend one day learning the underlying concepts, then dedicate the rest of the week to solving problems that reinforced them.
Trying to solve problems that rely on concepts you haven't learned yet is frustrating and inefficient. Study with intention, the time you invest in building strong fundamentals will pay off later.

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

> *"I solved 400+ LeetCode problems consistently. Still got stuck in interviews midway. Why? Because I didn't study patterns, I studied just problems."*

LeetCode isn't about memorizing 500 solutions. It's about mastering **~14 patterns** deeply. Once you do that, most problems will feel familiar.

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
<summary><b>📋 The 70-20-10 & 30-Minute Rules</b></summary>

### The 30-Minute Rule

Try to solve a problem on your own for **30 minutes**. If stuck:

1. Look at the solution/discussion
2. **Understand the pattern** — not just the code
3. Close it and rewrite the code yourself from scratch
4. This builds **active recall**, not passive recognition

> ⚠️ **The "Tutorial Fallacy"**: Watching a Neetcode video, nodding your head, and typing out his solution teaches you nothing. You learned how to watch someone else solve a problem, not how to solve it yourself.

### The 70-20-10 Rule

Spend your practice time on:
- **70%** on Medium problems
- **20%** on Hard problems
- **10%** on Easy problems

</details>

<details>
<summary><b>✍️ Practice Strategy: Quality Over Quantity</b></summary>

Your practice should follow this structure:

*   **The Foundation (Easy / Short Exercises):** Use straightforward problems to test your basic mastery of syntax and core data structures before moving forward.
*   **The Core Practice (Medium / Elaborate Problems):** Spend most of your time here. Focus on identifying optimization bottlenecks and understanding the *Best Conceivable Runtime (BCR)*. 
*   **The Methodology:** For every problem you tackle, do not jump straight to the computer. Solve it mentally, figure out the Big O time and space complexity, write your code **on paper**, test it manually on paper, and only then type it into a computer to log your mistakes.

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

Don't just solve a problem once and move on. The goal isn't to memorize solutions—it's to recognize patterns and build problem-solving intuition. Reviewing previously solved problems using **spaced repetition** is one of the most effective ways to make that knowledge stick.

Keeping a tracker also helps you identify weak topics, monitor your consistency, and quickly review important patterns before interviews.

Create a tracker (Notion, Google Sheets, or Excel) with the following columns:

| Column            | Purpose                                 |
| ----------------- | --------------------------------------- |
| Problem Name      | Title + LeetCode number                 |
| Topic             | Arrays, DP, Trees, etc.                 |
| Difficulty        | Easy / Medium / Hard                    |
| Status            | To Do / In Progress / Solved / Revised  |
| Date Solved       | Track consistency                       |
| Solution Approach | 1–2 sentences describing your intuition |
| Time Complexity   | Big-O analysis                          |
| Space Complexity  | Big-O analysis                          |
| Key Takeaway      | Pattern learned or common mistake       |
| Re-solved?        | Track reviews using spaced repetition   |

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
| **Neetcode** | [neetcode.io](https://neetcode.io) | Structured roadmap + video explanations |
| **Tech Interview Handbook** | [techinterviewhandbook.org](https://techinterviewhandbook.org) | Complete prep guide |
| **Pramp** | [pramp.com](https://pramp.com) | Free mock interviews |

### Books

| Book | Why |
|------|-----|
| **Cracking the Coding Interview** (Gayle Laakmann McDowell) | Classic — covers fundamentals and interview mechanics |
| **Elements of Programming Interviews** | More advanced — great for FAANG prep |

### YouTube Channels

| Channel | Best For |
|---------|----------|
| **Neetcode** | Visual explanations of LeetCode problems |
| **Take U Forward** | DSA fundamentals |

</details>

---

**Thanks for reading! :)**
