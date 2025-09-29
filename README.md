# DAA-Practical-4
Implementing maximum sum of subarray

Aim:
Implement maximum sum subarray using divide and conquer for a resource allocation scenario. Each task requires resources, and the goal is to maximize contiguous resource usage without exceeding a given constraint.

Problem Statement:
Given an array resources[i] representing the resources needed for each task, find the subarray that:
Maximizes resource utilization
Does not exceed a given constraint
Handles cases with no feasible subarray or multiple optimal subarrays

Key Cases Covered:
Small arrays (basic correctness)
Exact match to constraint
Single-element solution
No valid subarray (constraint too small)
Multiple optimal subarrays (ties allowed)
Large valid windows
Sliding window shrink adjustment
Edge cases: empty array, zero constraint
Stress test with very large input

Example:

Input: resources = [4, 2, 3, 1], constraint = 5

Output: Best subarray [2, 3] → sum = 5
