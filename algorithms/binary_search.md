# Binary Search

Binary search is one of the first algorithms, a pretty simple one, and represents the "Divide-and-Conquer" mind mapping, which is also used in other algorithms like backtracking.

1. In its most simplest form, binary search questions will ask you to find the first element equal to a value in a sorted array. [Example](https://leetcode.com/problems/search-insert-position/)
1. Then the next level would be to find the first element satisfying some condition in a sorted structure. [Example](https://leetcode.com/problems/first-bad-version/)
1. To expand the problem space, binary search can be applied to a problem with a fixed range of possible answers. [Example](https://leetcode.com/problems/furthest-building-you-can-reach/)

## Usages
1. The simplest one is pretty easy to spot.

1. The more complicated one, whether it's a BST, or some other sorted structure, is also straight-forward. (If there's a *sorted* mark somewhere in the known conditions.)

1. The hidden one, most likely at least a medium level problem, is harder to link with Binary Search. Ask yourself this:
    - Are we trying to find the largest/smallest possible answer?
    - Is it possible to use dynamic programming / memoization at first glance?
    - Is there both an upperbound and a lowerbound to the solution range?
    - Is it much easier to verify if an answer is correct than trying to find the right answer?