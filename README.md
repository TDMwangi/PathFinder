# A\* Pathfinding Algorithm

A* is a graph traversal and path search algorithm that is used in many fields of computer science due to its completeness, optimality, and optimal efficiency. It is a variant of Dijkstra's algorithm, which is used to find the shortest path between two nodes in a graph. However, A* is more efficient than Dijkstra's algorithm because it uses heuristics to guide its search.

![image info](./img/1.png)

```sh
f(n)=g(n)+h(n)
```

where:

- f(n) = total estimated cost of path through node n
- g(n) = cost so far to reach node n
- h(n) = estimated cost from n to goal. This is the heuristic part of the cost function, so it is like a guess
