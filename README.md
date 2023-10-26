This branch refers to general approaches to linked arrays, whether they are sorted or not. They include:
- Array element search (traverse)
- Subarray search
- Cycle detection
- Merge arrays
- Sort array

- https://www.youtube.com/watch?v=8hly31xKli0&ab_channel=freeCodeCamp.org

---

# Array traverse

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


---

# Merge arrays

- https://en.wikipedia.org/wiki/Merge_algorithm

### Merge Intervals

- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#4fd7
- https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/63923b23510946c22edc2e0a
- https://www.codingninjas.com/studio/library/given-n-appointments-find-all-conflicting-appointments
- https://leetcode.com/problems/merge-intervals/
- https://www.javatpoint.com/minimum-number-of-meeting-room-required-problem-in-java
- https://github.com/Chanda-Abdul/Several-Coding-Patterns-for-Solving-Data-Structures-and-Algorithms-Problems-during-Interviews/blob/main/%E2%9C%85%20%20Pattern%2004%20:%20Merge%20Intervals.md
- https://www.geeksforgeeks.org/merging-intervals/

### k-way merge algorithm

- https://en.wikipedia.org/wiki/K-way_merge_algorithm

---

# Array sorting algorithms

https://en.wikipedia.org/wiki/Sorting_algorithm

### Insertion sort

- Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Cliffo - Introduction to Algorithms - sec 2.1
- https://en.wikipedia.org/wiki/Insertion_sort

From chatGPT:
- InsertionSort has a time complexity of O(n^2) but can be efficient for small datasets.
- It's an in-place sorting algorithm and is often used for partially sorted data.

### Heapsort

- Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Cliffo - Introduction to Algorithms - chap 6
- https://en.wikipedia.org/wiki/Heapsort

From chatGPT:
- HeapSort has an average and worst-case time complexity of O(n log n).
- It's an in-place sorting algorithm that does not require additional memory for sorting.
- HeapSort is not as commonly used as QuickSort or MergeSort in practice.

From chatGPT:
- HeapSort has an average and worst-case time complexity of O(n log n).
- It's an in-place sorting algorithm that does not require additional memory for sorting.
- HeapSort is not as commonly used as QuickSort or MergeSort in practice.

### Quicksort

- Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Cliffo - Introduction to Algorithms - chap 7

From chatGPT:
- QuickSort is often considered one of the fastest sorting algorithms.
- It has an average-case time complexity of O(n log n), making it efficient for large datasets.
- QuickSort is an "in-place" algorithm, meaning it doesn't require additional memory.

### Cyclic sort

- https://en.wikipedia.org/wiki/Cycle_sort
- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#4a09
- https://leetcode.com/problems/kth-missing-positive-number/
- https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/
- https://leetcode.com/problems/find-all-duplicates-in-an-array/


From chatGPT:
- Cyclic Sort is an in-place sorting algorithm, meaning it doesn't require additional memory proportional to the input size.
- The time complexity of Cyclic Sort is O(n), making it efficient for sorting when the range of values is known.
- Cyclic Sort is particularly useful when sorting an array of integers within a specific known range. It efficiently places each element in its correct position in a cyclic manner.

### Block sort

- https://en.wikipedia.org/wiki/Block_sort

### Merge sort (by John Von Neumann <3)

- https://en.wikipedia.org/wiki/Merge_sort

From chat GPT:
- MergeSort has a stable O(n log n) time complexity.
- It's a "divide and conquer" algorithm that is not in-place, meaning it requires additional memory for merging.
- MergeSort is known for its predictability and is suitable for linked lists

[1]: https://en.wikipedia.org/wiki/Algorithmic_paradigm
[2]: https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed#67d7
