# Graphs
Graph $G = (V, E)$
- $V$ = set of vertices (arbitrary labels)
- $E$ = set of edges i.e. vertex pairs $(v, w)$

## Graph Representations
### Adjacency lists

```{figure} ../../../images/data-structure/adjacencyList.png
---
scale: 80%
name: adjacency-lists
---
```

### Object-oriented Variations
- object for each vertex $u$
- u.neighbors = list of neighbors i.e. Adj[u]

### Implicit Graphs
Adj(u) is a function — compute local structure on the fly which requires $\color{red}{\text{“Zero” Space}}$.

## Breadth-First Search
- visit all vertices reachable from given $s \in V$
- $O(V+E)$ time
- look at vertices reachable in 0 move ($s$), 1 move ($Adj[s]$), 2 moves, $\dotsc$
- be carefully to avoid $\color{red}{\text{duplicates}}$ 