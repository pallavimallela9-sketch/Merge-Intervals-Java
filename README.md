# Merge Intervals - Java

## Problem Statement

Given a collection of intervals, merge all overlapping
intervals.

## Example

Input:

[[1,3], [2,6], [8,10], [15,18]]

Output:

[[1,6], [8,10], [15,18]]

## Explanation

The intervals [1,3] and [2,6] overlap.

So they are merged into:

[1,6]

The remaining intervals do not overlap.

## Approach

1. Sort the intervals based on their starting values.
2. Compare each interval with the last interval in the result.
3. If they overlap, merge them.
4. Otherwise, add the new interval to the result.

## Complexity

- Time Complexity: O(n log n)
- Space Complexity: O(n)

## Language

Java

## Algorithm

Sorting and Interval Merging

## Author

M. Pallavi
