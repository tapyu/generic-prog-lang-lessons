# Informed search algorithm (shortest-path algorithms)

An informed search algorithm, also known as an informed or heuristic search, is a type of search algorithm that uses domain-specific knowledge, often represented as a heuristic function, to guide the search process. Unlike uninformed search algorithms, which explore the search space without any knowledge of the problem's specifics, informed search algorithms make use of additional information to make more informed decisions about which paths to explore.

The key component of an informed search algorithm is the heuristic function. This function provides an estimate of the cost or distance from the current state to the goal state. The algorithm uses this information to prioritize paths that seem more promising based on the heuristic estimate.

For example, in a map trajectory problem, an uninformed agent with no knowledge of Romanian geography has no clue whether going to Zerind or Sibiu is a better first step. In contrast, an informed agent who knows the location of each city knows that Sibiu is much closer to Bucharest and thus more likely to be on the **shortest path** (Russell, sec. 3.4).

General ref:

- https://en.wikipedia.org/wiki/List_of_algorithms
- https://en.wikipedia.org/wiki/Graph_traversal
- https://en.wikipedia.org/wiki/Tree_traversal
- https://stackoverflow.com/questions/1294720/whats-the-difference-between-backtracking-and-depth-first-search
- Stuart J. Russell - Artificial Intelligence_ A Modern Approach, Global Edition, sec 3.3, 3.5, and the beginning of chap 3
- Thomas H. Cormen - Introduction to Algorithms, beginning of the chapter 4
- https://en.wikipedia.org/wiki/Shortest_path_problem

## Best-first search

- https://en.wikipedia.org/wiki/Best-first_search
- https://www.analyticsvidhya.com/blog/2023/09/best-first-search-in-artificial-intelligence
- Stuart J. Russell - Artificial Intelligence_ A Modern Approach, Global Edition, sec 3.5.1

## A∗ search

[Special][1] case of best-first search that uses heuristics to improve speed.

- Stuart J. Russell - Artificial Intelligence_ A Modern Approach, Global Edition, sec 3.5.2
- https://en.wikipedia.org/wiki/A*_search_algorithm

## Dijkstra's algorithm

[A special][2] case of A* for which no heuristic function is used. Computes shortest paths in a graph with non-negative edge weights.

- https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm
- Thomas H. Cormen - Introduction to Algorithms, sec 22.3
- Rosen, Kenneth H - Discrete mathematics and its applications, sec 10.6

## Floyd–Warshall algorithm

- Thomas H. Cormen - Introduction to Algorithms, sec 23.2

## Bellman–Ford algorithm

- Thomas H. Cormen - Introduction to Algorithms, sec 22.1

## Viterbi algorithm

See my master thesis.

[1]: https://en.wikipedia.org/wiki/List_of_algorithms