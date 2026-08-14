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
<summary><b>Core Topics to Master Before Grinding</b></summary>

Don't jump straight into solving LeetCode problems without understanding the fundamentals first!!!
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

### ✍️ Practice Strategy: Quality Over Quantity

Your practice should follow this structure:

* **The Foundation (Easy / Short Exercises):** Use straightforward problems to test your basic mastery of syntax and core data structures before moving forward.
* **The Core Practice (Medium / Elaborate Problems):** Spend most of your time here. Focus on identifying optimization bottlenecks and understanding the *Best Conceivable Runtime (BCR)*.
* **The Methodology:** For every problem, don't jump straight to the computer. Solve it mentally, determine the Big O time and space complexity, write your code **on paper**, test it manually, and only then type it into a computer to review mistakes.

### 🎯 Mock Interviews: Practice the Real Skill

**Do many mock interviews.** Solving LeetCode alone is much easier than solving while being interviewed.

During my preparation, I did a mock interview about every two weeks with my mentor. He gave me a random problem from a topic I had already studied, preferably **outside the NeetCode 250**, and used follow-up questions to make the interview less predictable.

The goal was not to memorize solutions. It was to practice solving unfamiliar problems in ~30 minutes while simultaneously:

* thinking out loud;
* explaining my approach and trade-offs;
* writing code;
* listening to the interviewer;
* responding to follow-ups;
* adapting when something unexpected happened.

This is a surprisingly demanding form of multitasking. **The more mocks you do, the more natural the interview format becomes and the less mental energy you spend dealing with the pressure itself.**

### Weekly Study Plan (12 Months)

There is no universal “right” pace for interview preparation. It depends on your background, available time, and familiarity with the material.

I personally spent **about a year preparing** at a relatively slow pace. Coming from Industrial Engineering rather than Computer Science, I had to learn many DSA concepts from scratch. Taking my time helped me understand the patterns instead of simply maximizing my problem count.

The plan below follows the **NeetCode 250 topic order**, with enough time for practice, review, and deeper understanding.

| Weeks | Focus                          |
| ----- | ------------------------------ |
| 1–3   | Arrays & Hashing               |
| 4–5   | Two Pointers                   |
| 6–7   | Sliding Window                 |
| 8–9   | Stack                          |
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
