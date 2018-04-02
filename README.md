# Reboot Tutorials

A set of semi-interactive chapters on computer science, competitive programming, and informatics.

For the PSHS-MC competitive programming team.

## Modules

Aside from required prerequisites, the modules are self-contained. We want to enable flexibility with how a student learns core informatics concepts on their own, especially since training sessions are unpredictable. We do suggest that concepts are tackled in order of the number of each module.

The modules tackle all computer science concepts tackled in the NOI and the IOI. We do assume that students have prior programming experience in C++, to the level of PSHS's Computer Science 2 subject.

### `00-ICS` Introduction to Computer Science

An overview of the motivations behind modeling and solving complex problems, along with the core competencies needed to analyze and code up solutions.

* `ICS-00` Solving problems
* `ICS-07` Modeling; overview of ADTs and data structures
* `ICS-02` C++ refresher; parsing input
* `ICS-03` Exploring the C++ STL
* `ICS-04` Analysis of algorithms; searching
* `ICS-05` Big O notation; sorting
* `ICS-06` Recursion and memory management
* `ICS-01` Anatomy of the competitive programming problem

### `01-LTD` Linear and Tree Data Structures

How we model and organize data, and algorithms on how to operate on them. Covers stacks, queues, maps, sets, and the data structures underlying them.

Prerequisites: `00-ICS`

Tentative coverage:
* **ADT:** Stacks and queues
    * Definition and motivation
    * Methods
* Resizing arrays
    * Definition
    * Access, traversal, insertion, deletion
    * Resizing an array; amortized analysis
* Linked lists
    * Definitions
    * Access, traversal
    * Insertion, deletion
    * Singly and doubly-linked lists
    * Circular lists
* **ADT:** Sets and maps
    * Definition and motivation
    * Methods
* Binary search trees
    * Definitions
    * Access, insertion
    * Tree traversals
    * Assorted queries
* Balanced binary search trees
    * Worst-case BST analysis
    * Tree rotations
    * Determining when to rotate
* Hash tables
    * Definitions; the hash function
    * Access, insertion, traversal, removal
    * Handling collisions
* **ADT:** Priority queues
    * Definition and motivation
    * Methods
* Heaps
    * Definitions
    * Insertion/sinking
    * Removal/swimming
    * Heapsort



### `O2-BGT` Beginner graph theory

The study of networks and problems that deal with them.

Tentative coverage:
* Graph definitions
    * Nodes and edges
    * Directed and undirected graphs
    * Degrees and weights
    * Cycles, paths, and walks
    * Eulerian and Hamiltonian paths
* Graph representations
    * Edge list
    * Adjacency list
    * Adjacency matrix
* **Problem:** Minimum spanning tree
    * Definitions
    * Prim's algorithm
    * Kruskal's algorithm; the union-find data structure
* **Problem:** Shortest path
    * Definitions; relaxing an edge
    * Single-source: Djikstra's
    * Single-source: Bellman-Ford
    * All-pairs: Floyd-Warshall
* Directed acyclic graphs
    * Definitions and motivation
    * Topological sorting
    * **Problem:** The critical path

### Future topics

* Discrete mathematics
    * Induction
    * Number theory
    * Counting; combinations and permutations
* Geometry and computational geometry
* Algorithmic paradigms
    * Divide and conquer
    * Greedy algorithms
    * Dynamic programming
* Intermediate graph theory
    * Connected components
    * Maximum flow/minimum cut
