# DSA Interview Preparation

> A focused practice workspace for a senior Java full-stack developer with 10 years of experience.

This repository is for interview-quality problem solving, not for collecting random solutions. Each solution should show clear reasoning, production-quality Java, correct complexity analysis, and awareness of edge cases.

## Interview Target

| Area | Preparation outcome | Status |
| --- | --- | --- |
| Data structures and algorithms | Solve medium problems in 25-35 minutes | [ ] |
| Problem-solving communication | Clarify requirements, explain trade-offs, and verify with examples | [ ] |
| Java implementation | Use the right collection, comparator, API, and class design | [ ] |
| Code quality | Write readable, testable, defensive code | [ ] |
| Senior-level discussion | Explain scalability, failure modes, and alternatives | [ ] |
| Mock interviews | Complete 6 timed sessions | [ ] |

## Working Principles

1. Understand the pattern before memorizing the solution.
2. Start with a brute-force approach, then improve it deliberately.
3. State invariants and complexity before writing the final code.
4. Test empty input, one element, duplicates, negative values, overflow, and boundary indexes.
5. Re-solve failed problems after 24 hours and again after 7 days.
6. Prefer 120 well-understood problems over 500 copied solutions.

## Eight-Week Plan

| Week | Focus | Minimum outcome | Done |
| ---: | --- | --- | --- |
| 1 | Arrays, strings, hashing | 12 problems and a Java collections review | [ ] |
| 2 | Two pointers, sliding window, prefix sums | 12 problems and pattern notes | [ ] |
| 3 | Sorting, binary search, intervals | 10 problems and reusable templates | [ ] |
| 4 | Linked lists, stacks, queues, monotonic stack | 12 problems and implementations from scratch | [ ] |
| 5 | Trees, BST, heaps, priority queues | 12 problems and traversal templates | [ ] |
| 6 | Graph traversal, topological sort, shortest path | 12 problems and graph representation notes | [ ] |
| 7 | Recursion, backtracking, greedy, dynamic programming | 12 problems and state-transition notes | [ ] |
| 8 | Mixed revision and mock interviews | 6 mocks, error review, and final weak-area revision | [ ] |

## Daily Practice Log

Copy this section for each session. Keep the latest session at the top.

### YYYY-MM-DD | Topic: | Duration:  minutes

| Step | Notes |
| --- | --- |
| Problem(s) |  |
| Pattern identified |  |
| Initial approach |  |
| Final approach |  |
| Time / space complexity |  |
| Edge cases tested |  |
| What I learned |  |
| Follow-up problem |  |
| Solution links |  |

Daily checklist:

- [ ] Clarify inputs, outputs, constraints, and examples
- [ ] Identify a brute-force solution
- [ ] Explain the optimized pattern before coding
- [ ] Implement in Java without relying on an IDE shortcut
- [ ] Test normal, boundary, and adversarial cases
- [ ] Record complexity and one improvement
- [ ] Mark the problem as `Solved`, `Review`, or `Blocked`

## Pattern Checklist

### Arrays, Strings, and Hashing

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | Frequency map / set | Two Sum, Contains Duplicate, Group Anagrams |
| [ ] | Prefix sum | Subarray Sum Equals K, Range Sum Query |
| [ ] | Difference array | Range updates, meeting-room capacity |
| [ ] | Kadane's algorithm | Maximum Subarray, Maximum Product Subarray |
| [ ] | Matrix traversal | Spiral Matrix, Rotate Image, Set Matrix Zeroes |
| [ ] | In-place manipulation | Move Zeroes, Sort Colors, Merge Sorted Array |
| [ ] | String window | Longest Substring, Minimum Window Substring |
| [ ] | Character counting | Valid Anagram, Find All Anagrams |

### Two Pointers, Windows, and Intervals

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | Opposite-direction pointers | Two Sum II, Valid Palindrome, Container With Most Water |
| [ ] | Fast and slow pointers | Linked-list cycle, middle node, happy number |
| [ ] | Fixed-size window | Maximum Sum Subarray of Size K |
| [ ] | Variable-size window | Minimum Size Subarray Sum, Fruit Into Baskets |
| [ ] | Merge intervals | Merge Intervals, Insert Interval |
| [ ] | Interval scheduling | Meeting Rooms, Non-overlapping Intervals |

### Search and Sorting

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | Binary search on sorted data | Search Insert Position, First and Last Position |
| [ ] | Binary search on answer | Capacity to Ship, Split Array Largest Sum |
| [ ] | Divide and conquer | Merge Sort, Count Inversions |
| [ ] | Heap selection | Kth Largest Element, Top K Frequent Elements |
| [ ] | Custom ordering | Largest Number, Sort Characters by Frequency |

### Linked List, Stack, and Queue

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | Pointer rewiring | Reverse List, Merge Two Sorted Lists |
| [ ] | Sentinel node | Remove Nth Node, Merge Lists |
| [ ] | Monotonic stack | Daily Temperatures, Next Greater Element |
| [ ] | Stack parsing | Valid Parentheses, Evaluate RPN |
| [ ] | Deque window | Sliding Window Maximum |
| [ ] | Design structure | Min Stack, LRU Cache |

### Trees, Heaps, and Graphs

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | DFS recursion | Maximum Depth, Diameter, Path Sum |
| [ ] | BFS by level | Level Order, Zigzag Traversal, Word Ladder |
| [ ] | BST invariant | Validate BST, Kth Smallest, LCA |
| [ ] | Heap / priority queue | Merge K Lists, Median from Data Stream |
| [ ] | Graph BFS / DFS | Number of Islands, Clone Graph |
| [ ] | Topological ordering | Course Schedule, Alien Dictionary |
| [ ] | Shortest path | Dijkstra, 0-1 BFS, Bellman-Ford |
| [ ] | Union-find | Number of Provinces, Accounts Merge |

### Recursion, Greedy, and Dynamic Programming

| Done | Pattern | Representative practice |
| --- | --- | --- |
| [ ] | Backtracking | Subsets, Permutations, Combination Sum |
| [ ] | Greedy invariant | Jump Game, Gas Station, Task Scheduling |
| [ ] | 1D state | Climbing Stairs, House Robber, Decode Ways |
| [ ] | Grid state | Unique Paths, Minimum Path Sum, Word Search |
| [ ] | Knapsack state | Coin Change, Partition Equal Subset Sum |
| [ ] | Sequence state | LIS, LCS, Edit Distance |

## Java Interview Checklist

| Done | Topic | What to be able to explain |
| --- | --- | --- |
| [ ] | `ArrayList` vs `LinkedList` | Access, insertion cost, memory, and practical choice |
| [ ] | `HashMap` and `HashSet` | Hashing, collisions, resizing, `equals`, and `hashCode` |
| [ ] | `TreeMap` and `TreeSet` | Ordering, comparator behavior, and logarithmic operations |
| [ ] | `PriorityQueue` | Min/max heap behavior and custom comparators |
| [ ] | `ArrayDeque` | Stack and queue usage without legacy `Stack` |
| [ ] | Sorting APIs | `Comparator`, stable sorting, null handling, and overflow-safe comparison |
| [ ] | Generics | Type safety, wildcards, and reusable data-structure APIs |
| [ ] | Streams and lambdas | When they improve clarity and when a loop is better in an interview |
| [ ] | Immutability | Defensive copies, final fields, and safe object design |
| [ ] | Integer handling | `long` for sums/products and avoiding comparator subtraction overflow |
| [ ] | Testing | JUnit tests for happy paths, boundaries, duplicates, and invalid input |

## Senior-Level Follow-Up Questions

For each important problem, answer at least two of these:

- What changes if the input does not fit in memory?
- Can the solution be streamed or processed incrementally?
- What is the concurrency model if multiple requests use this structure?
- How would you make the API immutable or thread-safe?
- What happens under worst-case hash collisions or skewed input?
- How would you instrument, test, and monitor this in production?
- What trade-off changes if latency matters more than memory?
- Which part would you extract into a reusable service or library?

## Problem Register

| # | Problem | Pattern | Difficulty | Status | Date | Solution |
| ---: | --- | --- | --- | --- | --- | --- |
| 1 |  |  | Easy / Medium / Hard | Planned |  |  |
| 2 |  |  | Easy / Medium / Hard | Planned |  |  |
| 3 |  |  | Easy / Medium / Hard | Planned |  |  |

Status values: `Planned` | `In Progress` | `Solved` | `Review` | `Blocked`

## Review Queue

| Review date | Problem | Failure reason | Correct pattern | Re-solved |
| --- | --- | --- | --- | --- |
|  |  |  |  | [ ] |

Recommended review intervals: same day, 24 hours, 7 days, and 30 days.

## Weekly Review

### Week of YYYY-MM-DD

| Metric | Result |
| --- | --- |
| Problems attempted |  |
| Problems solved without help |  |
| Problems needing review |  |
| Mock interview score |  |
| Strongest pattern |  |
| Weakest pattern |  |
| Next week's focus |  |

- [ ] I can explain the main patterns without notes.
- [ ] I re-solved every blocked problem.
- [ ] I completed one timed mixed set.
- [ ] I updated the problem register and review queue.
- [ ] I wrote one senior-level follow-up for each major topic.

## Solution Template

Create one Markdown note per problem using this format.

```markdown
# Problem Name

- Difficulty:
- Pattern:
- Source:
- Status:

## Clarification

## Examples and Edge Cases

## Brute Force

## Optimized Approach

## Correctness Invariant

## Java Solution

## Complexity

- Time:
- Space:

## Follow-up Discussion

## Mistake and Review Date
```

## Definition of Ready

- [ ] Solve 2 unseen medium problems consecutively within 60 minutes.
- [ ] Explain the pattern, invariant, and complexity while coding.
- [ ] Implement common structures using Java collections and custom classes.
- [ ] Complete 6 mock interviews with clear communication.
- [ ] Re-solve all problems marked `Review` or `Blocked`.
- [ ] Discuss at least one scalability or production follow-up per mock.

## Suggested Repository Layout

```text
DSA-Interview/
|-- README.md
|-- arrays-strings/
|-- hashing-patterns/
|-- two-pointers-sliding-window/
|-- search-sort-intervals/
|-- linked-list-stack-queue/
|-- trees-heaps/
|-- graphs/
|-- recursion-greedy-dp/
|-- java-reference/
|-- solutions/
|-- mocks/
`-- review-notes/
```
