## Algorithmic paradigm

[An algorithmic][1] paradigm or algorithm design paradigm is a generic model or framework which underlies the design of a class of algorithms. An algorithmic paradigm is an abstraction higher than the notion of an algorithm, just as an algorithm is an abstraction higher than a computer program.

More info:

- https://levelup.gitconnected.com/dont-just-leetcode-follow-the-coding-patterns-instead-4beb6a197fdb?gi=097845554131
- https://www.designgurus.io/blog/Grokking-the-Coding%20Interview-Patterns
- https://interviewnoodle.com/top-leetcode-patterns-for-faang-coding-interviews-bdbe8766534c
- https://grokkingtechinterview.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed
- Rosen, Kenneth H - Discrete mathematics and its applications - Sec. 3.3.4

---

## Backtracking

### Depth-First search (DFS)

While [backtracking][2] is a more general purpose algorithm, depth-First search is a specific form of backtracking related to searching tree structures. It starts at the root (selecting some node as the root in the graph case) and explores as far as possible along each branch before backtracking. It uses backtracking as part of its means of working with a tree, but is limited to a tree structure.

On the other hand, backtracking can be used on any type of structure where portions of the domain can be eliminated - whether or not it is a logical tree. The Wiki example uses a chessboard and a specific problem - you can look at a specific move, and eliminate it, then backtrack to the next possible move, eliminate it, etc.

TODO:

- https://en.wikipedia.org/wiki/Backtracking
- https://en.wikipedia.org/wiki/Depth-first_search
- Cormen: Introduction to algorithms, sec. 20.3
- Rosen, Kenneth H - Discrete mathematics and its applications, sec 11.4.2 
- https://leetcode.com/tag/backtracking/
- https://leetcode.com/tag/depth-first-search/

[1]: https://en.wikipedia.org/wiki/Algorithmic_paradigm
[2]: https://stackoverflow.com/questions/1294720/whats-the-difference-between-backtracking-and-depth-first-search/1294741#1294741
