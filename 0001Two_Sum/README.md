# Two Sum Problem Solution in C

This repository contains a solution for a well-known problem in computer science called the "Two Sum" problem.

## Problem Statement

Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

The function twoSum has the following parameters:

- `nums`: an array of integers
- `N`: the number of elements in `nums`
- `target`: the target integer
- `returnSize`: a pointer to an integer which will store the size of the returned array

### Constraints

- 2 <= nums.length <= 10^4
- -10^9 <= nums[i] <= 10^9
- -10^9 <= target <= 10^9
- Only one valid answer exists.

## Solution

The solution provided in this repository uses a simple double loop to iterate over the array. It checks all pairs of numbers to find a pair that adds up to the target number.

The function `twoSum` has a time complexity of O(n^2), where n is the number of elements in `nums`. The space complexity is O(1), excluding the output space.
