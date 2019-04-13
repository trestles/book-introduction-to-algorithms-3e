

## I Foundations
#### 1 The Role of Algorithms in Computing
- 1.1 Algorithms 5
- 1.2 Algorithms as a Technology 11

#### 2 Getting Started 
- 2.1 Insertion Sort p16
- 2.2 Analyzing Algorithms p23
- 2.3 Designing Algorithms p29

#### 3 Growth of Functions 43
- 3.1 Asymptotic Notation p43
- 3.2 Standard Notations and Common Functions p53

#### 4 Divide and Conquer p65
- 4.1 The maximum-subarray problem p68
- 4.2 Strassen's algorithm for matrix multiplication p75
- 4.3 The substitution method for solving recurrences p83
- 4.4 The recursion tree method for solving recurrences p88
- 4.5 The master method for solving recurrences p93
- 4.6 Proof of the master method p97

#### 5 Probabilistic Analysis and Randomized Algorithms p114
- 5.1 The hiring problem p114
- 5.2 Indicator random variables p118
- 5.3 Randomized algorithms p122
- 5.4 Probabilistic analysis and further uses of indicator random variables p130

## II Sorting and Order Statistics 
#### 6 Heapsort p151
- 6.1 Heaps p151
- 6.2 Maintaining the heap property p154
- 6.3 Building a heap p156
- 6.4 The heapsort algorithm p159
- 6.5 Priority queues p162

#### 7 Quicksort p170
- 7.1 Description of quicksort p170
- 7.2 Performance of quicksort p174
- 7.3 A randomized version of quicksort p179
- 7.4 Analysis of quicksort p180

#### 8 Sorting in Linear Time p191
- 8.1 Lower bounds for sorting p191
- 8.2 Counting sort p194
- 8.3 Radix sort p197
- 8.4 Bucket sort p200

#### 9 Medians and Order Statistics p213
- 9.1 Minimum and maximum p214
- 9.2 Selection in expected linear time p215
- 9.3 Selection in worst-case linear time p220

## III Data Structures
#### 10 Elementary Data Structures
- 10.1 Stacks and queues p232
- 10.2 Linked lists p236
- 10.3 Implementing pointers and objects p241
- 10.4 Representing rooted trees p246

#### 11 Hash Tables p253
- 11.1 Direct-address tables p254
  - Figure 11.1 p254
- 11.2 Hash tables p256
  - Figure 11.2 p256
  - Figure 11.3 p257
  - Collusion resolution by chaining p257
  - Analysis of hashing with chaining p258
    - simple uniform hashing p259
    - Theorem 11.1 p259
      - Proof p259
    - Theorem 11.2 p259
      - Proof p259
- 11.3 Hash functions p262
  - What makes a good hash function? p262
  - Interpreting keys as natural numbers p263
  - 11.3.1 The division method p263
  - 11.3.2 The multiplication method p263
    - Figure 11.4 
  - 11.3.3 * Universal hashing p265
    - Theorem 11.3 p265
      - Proof p265
    - Corollary 11.4 p266
      - Proof p266
    - Designing a universal class of hash functions p267
      - Theorem 11.5 p267
        - Proof p267
- 11.4 Open addressing p269
  - HASH-INSERT(T, k) p270
  - HASH-SEARCH(T, k) p271
  - Linear probing p272
  - Quadratic probing p272
  - Double hashing p272
  - Analysis of open-address hashing p274
    - Theorem 11.6 p274
      - Proof p274
    - Corollary 11.7 p276
      - Proof p276
    - Theorem p276
- 11.5 *Perfect hashing p277
  - Theorem 11.9 p279
    - Proof p279
  - Theorem 11.10 p280
    - Proof p280
  - Corollary 11.11 p281
    - Proof p281
  - Corollary 11.12 p281
    - Proof p282
  - Exercises p282

#### 12 Binary Search Trees p286
- 12.1 What is a binary search tree? p286
  - Figure 12.1 p287
  - INORDER-TREE-WALK(x) p288
  - Theorem 12.1 p288
    - Proof p288
  - Exercises p289
- 12.2 Querying a binary search tree p289
  - Searching p289
  - Minimum and Maximum p291
  - Successor and predecessor p291
  - Theorem 12.2
- 12.3 Insertion and deletion p294
  - Insertion p294
    - Figure 12.3
  - Deletion p295
    - Figure 12.4 p297
  - Theorem 12.3 p298
  - Exercises p299
- 12.4 * Randomly build binary search trees p299

#### 13 Red-Black Trees p308
- 13.1 Properties of red-black trees p308
- 13.2 Rotations p312
- 13.3 Insertion p315
- 13.4 Deletion p323

#### 14 Augmenting Data Structures p339
- 14.1 Dynamic order statistics p339
- 14.2 How to augment a data structure p345
- 14.3 Interval trees p348

## IV Advanced Design and Analysis Techniques 
#### 15 Dynamic Programming p359
- 15.1 Rod Cutting p360
- 15.2 Matrix-chain multiplication p370
- 15.3 Elements of dynamic programming p378
- 15.4 Longest common subsequence p390
- 15.5 Optimal binary search trees p397

#### 16 Greedy Algorithms p414
- 16.1 An activity-selection problem p415
- 16.2 Elements of the greedy strategy p423
- 16.3 Huffman codes p428
- 16.4 * Matroids and greedy methods p437
- 16.5 * A task-scheduling problem as a matroid p443

#### 17 Amortized Analysis p451
- 17.1 Aggregate analysis p452
- 17.2 The accounting method p456
- 17.3 The potential method p459
- 17.4 Dynamic tables p463

## V Advanced Data Structures 
#### 18 B-Trees p484
- 18.1 Definition of B-trees p485
- 18.2 Basic operation on B-trees p491
- 18.3 Deleting a key from a B-tree p499

#### 19 Fibonacci Heaps p505
- 19.1 Structure of Fibonacci heaps p507
- 19.2 Mergeable-heap operations p510
- 19.3 Decreasing a key and deleting a node p518
- 19.4 Bounding the maximum degree p523

#### 20 van Emde Boas Trees p531
- 20.1 Preliminary approaches p532
- 20.2 A recursive structure p536
- 20.3 The van Emde Boas tree p545

#### 21 Data Structures as Disjoint Sets p561
- 21.1 Disjoint-set operations p561
- 21.2 Linked-list representation of disjoint sets p564
- 21.3 Disjoint-set forests p568
- 21.4 * Analysis of union by rank with path compression p573

## VI Graph Algorithms 
#### 22 Elementary Graph Algorithms p589
- 22.1 Representations of Graphs p589
- 22.2 Breadth-first search p594
- 22.3 Depth-first search p603
- 22.4 Topological sort p612
- 22.5 Strongly connected components p615

#### 23 Minimum Spanning Trees p624
- 23.1 Growing a minimum spanning tree p625
- 23.2 The algorithms of Kruskal and Prim p631

#### 24 Single-Source Shortest Paths p643
- 24.1 The Bellman-Ford algorithm p651
- 24.2 Single-source shortest paths in directed acyclic graphs p655
- 24.3 Dijkstra's algorithm p658
- 24.4 Difference constraints and shortest paths p664
- 24.5 Proofs of shortest-path properties p671

#### 25 All-Pairs Shortest Paths p684
- 25.1 Shortest paths and matrix multiplication p686
- 25.2 The Floyd-Warshall algorithm p693
- 25.3 Johnson's algorithm for sparse graphs p700

#### 26 Maximum Flow p708
- 26.1 Flow Networks p709 
- 26.2 The Ford-Fulkerson Method p714
- 26.3 Maximum bipartite matching p732
- 26.4 * Push-relabel algorithms p736
- 26.5 * The relabel-to-front algorithm p748

## VII Selected Topics

## VIII Appendix: Mathematical Background
#### A Summations p1145
- A.1 Summation formulas and properties p1145
- A.2 Bounding summations p1149

#### B Sets, Etc. p1158
- B.1 Sets p1158
- B.2 Relations p1163
- B.3 Functions p1166
- B.4 Graphs p1168
- B.5 Trees p1173 

#### C Counting and Probability p1183
- C.1 Counting p1183
- C.2 Probability p1189
- C.3 Discrete Random Variables p1196
- C.4 The geometric and binomial distributions p1201
- C.5 * The tails of the binomial distribution p1208

#### D Matrices p1217
- D.1 Matrices and matrix operations p1217
- D.2 Basic matrix properties p1222