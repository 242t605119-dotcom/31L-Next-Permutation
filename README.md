# LeetCode 31 - Next Permutation

## Problem

Given an array of integers, rearrange the numbers into the next lexicographically greater permutation.

If no greater permutation is possible, rearrange the array into the smallest possible order.

The changes must be made in-place.

## Example

Input:

```text
nums = [1, 2, 3]
```

Output:

```text
[1, 3, 2]
```

## Approach

First, I find the first number from the right that is smaller than the number after it.

Then I find the next greater number from the right and swap them.

Finally, I reverse the remaining part of the array to get the next permutation.

## Complexity

* Time Complexity: `O(n)`
* Space Complexity: `O(1)`

## Topics

* Array
* Two Pointers

## Language

Python

## Author

T.Nandhini
