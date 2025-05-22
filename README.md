# Day23-50-days-coding-challenge
 Problem 1: Longest Valid Parentheses

📌 Problem Statement:
Given a string containing just the characters '(' and ')', return the length of the longest valid (well-formed) parentheses substring.

📌 Constraints:

0 ≤ s.length ≤ 30,000

s[i] is either '(' or ')'

📌 Approach:

Stack-based solution: Track indices of unmatched parentheses and compute max distance between valid pairs.

Dynamic programming: Track lengths of valid substrings ending at each index for optimal performance.

📌 Examples:
Input: "(()" → Output: 2
Input: ")()())" → Output: 4
Input: "" → Output: 0

🔸 Problem 2: Search Insert Position

📌 Problem Statement:
Given a sorted array of distinct integers and a target value, return the index if the target is found.
If not, return the index where it would be inserted in order.

📌 Constraints:

1 ≤ nums.length ≤ 10⁴

-10⁴ ≤ nums[i], target ≤ 10⁴

nums is sorted in ascending order with distinct elements.

📌 Approach:

Classic binary search to find the target or insertion point in O(log n) time.

📌 Examples:
Input: [1,3,5,6], target: 5 → Output: 2
Input: [1,3,5,6], target: 2 → Output: 1
Input: [1,3,5,6], target: 7 → Output: 4

🔹 Topics Covered:

Stack

Dynamic Programming

Binary Search

String Parsing

Leetcode
