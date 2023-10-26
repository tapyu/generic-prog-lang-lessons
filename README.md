This branch refers to general approaches to linked arrays, whether they are sorted or not. They include:
- Array element search (traverse)
- Subarray search
- Cycle detection
- Merge arrays
- Sort array

- https://www.youtube.com/watch?v=8hly31xKli0&ab_channel=freeCodeCamp.org

## Two pointers

"Two Pointers" is a technique where you use two pointers that iterate through the data structure (such as an array or linked list) at different speeds. The pointers can move towards each other, away from each other, or in some other pattern.

- https://leetcode.com/tag/two-pointers/
- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#b5df

- https://leetcode.com/problems/squares-of-a-sorted-array/
- https://www.educative.io/answers/the-dutch-national-flag-problem-in-cpp
- https://leetcode.com/problems/shortest-unsorted-continuous-subarray/

### Fast and Slow pointers (cycle detection)

While "Two Pointers" is a general technique involving two pointers, "Fast and Slow pointers" is a specific instance of this technique where the pointers move at different speeds. The Fast and Slow pointers technique is often associated with linked list problems, but the Two Pointers technique can be applied to a broader range of algorithmic problems. By moving at different speeds (say, in a cyclic linked list), the algorithm proves that the two pointers are bound to meet.

- https://en.wikipedia.org/wiki/Cycle_detection
- https://leetcode.com/problems/middle-of-the-linked-list/
- https://leetcode.com/problems/happy-number/
- https://leetcode.com/problems/circular-array-loop/

### Floyd's cycle-finding algorithm (also known as Hare & Tortoise algorithm)

The Floyd's cycle-finding algorithm is a specific application of the Fast and Slow pointers technique, which is a subset of the broader Two Pointers technique. In the context of cycle detection in linked lists, Floyd's algorithm uses two pointers, one moving at twice the speed of the other.

The "tortoise and hare algorithm" is often used as a colloquial term for Floyd's cycle-finding algorithm. In this algorithm, there are two pointers, one referred to as the "tortoise" (slow pointer) and the other as the "hare" (fast pointer). The algorithm is used to detect cycles in linked lists.

### Sliding window

- https://medium.com/@rishu__2701/mastering-sliding-window-techniques-48f819194fd7
- https://www.geeksforgeeks.org/window-sliding-technique/
- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#4a09
- https://www.designgurus.io/blog/Grokking-the-Coding%20Interview-Patterns
- https://leetcode.com/tag/sliding-window/
- https://leetcode.com/problems/fruit-into-baskets/
- https://www.codingninjas.com/studio/problems/longest-substring-with-at-most-k-distinct-characters_2221410


### Merge Intervals

- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#4fd7
- https://www.codingninjas.com/studio/library/given-n-appointments-find-all-conflicting-appointments
- https://leetcode.com/problems/merge-intervals/
- https://www.javatpoint.com/minimum-number-of-meeting-room-required-problem-in-java
- https://www.geeksforgeeks.org/merging-intervals/


### Cyclic sort

- https://en.wikipedia.org/wiki/Cycle_sort
- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#4a09
- https://leetcode.com/problems/kth-missing-positive-number/
- https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/
- https://leetcode.com/problems/find-all-duplicates-in-an-array/

[1]: https://en.wikipedia.org/wiki/Algorithmic_paradigm
[2]: https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#67d7
