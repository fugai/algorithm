### Overview 

This repository contains the Rust source code 
for the algorithms in the textbook 
[Algorithms, 4th Edition](http://amzn.to/13VNJi7) 
by Robert Sedgewick and Kevin Wayne.

The official Java source code is 
[here](https://github.com/kevin-wayne/algs4).

### Goals

Make a Rust implementation of the library so that
a Rust programmer can follow this book easily or
prefer to demonstrate the algorithms using Rust.

Try to keep the interface and variable name consistent
with the original book while writing idiomatic rust
code.

I hope that this project helped you understand why 
Rust is so wonderful and loved right now. Rust is proving 
to be a productive tool for reliable and efficient software. 
In Rust, the compiler plays
a gatekeeper role by refusing to compile code with
these elusive bugs, including concurrency bugs.
By working alongside the compiler, you can spend your
time focusing on the program’s logic rather than
chasing down bugs. After you finish a day's work,
go home and rest, can be at ease a good night's sleep,
never worry about system crash.

### Index

#### Fundamentals 

- find the largest M elements (TopM)
- priority queue (PQ)
- union find (UF)
- LinkedList
- Queue
- Stack

#### Graphs

- directed graph
  - cycle detection (DirectedCycle, EdgeWeightedDigraphCycle)
  - strong connectivity in digraphs (KosarajuSCC)
  - topological sort (Topological)
  - transitive closure (TransitiveClosure)
  - Finding paths (DepthFirstPaths, BreadthFirstPaths)
- minimum spanning trees 
  - Lazy version of Prim’s MST algorithm (LazyPrimMST)
  - Prim’s algorithm (PrimMST)
  - Kruskal’s algorithm (KruskalMST)
- shortest paths
  - arbitrage problem (Arbitrage)
  - Acyclic edge-weighted digraphs (AcyclicSP, AcyclicLP)
  - Critical path method for parallel precedence-constrained job scheduling (CPM)
  - Dijkstra’s algorithm (DijkstraSP, DijkstraAllPairsSP)
  - Bellman-Ford algorithm (BellmanFordSP) 
- undirected graph
  - bipartite (Bipartite)
  - connected components (CC)
  - cycle detection (Cycle)
  - depth first search (DepthFirstSearch, NonRecursiveDFS)
  - Finding paths (DepthFirstPaths, BreadthFirstPaths)
  - Symbol graphs (SymbolGraph)

#### Searching

- Binary Search (binary.rs)
- Binary Search Tree (bst.rs)
- Red black (rb2.rs)

#### Sorting

- Bubble Sort (bubble.rs)
- Insertion Sort (insert.rs)
- Merge Sort (merge.rs)
- Quick Sort (quick.rs)
- Robert. W. Floyd Heap sort (floyd.rs)
- Selection Sort (selection.rs)
- Shell's Sort (shell.rs)
- Tournament Tree Sort (tree_selection.rs)

#### Strings

- Character-indexed arrays (Alphabet, count.rs)
- radix sort (LSD, MSD)

### Running

```
# setup Rust Toolchain
make test
```

### Roadmap

- Implement algorithms in the textbook
  [Algorithms, 4th Edition](http://amzn.to/13VNJi7)
- Algorithms visualization (Easy to study and short learning curve)