

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
  - Asymptotic notation, functions, and running times p44
  - Theta - notation p44
  - Big-O-Notation p47
  - Omega Notation p48
  - Asymptotic notation in equations and inequalities p49
- 3.2 Standard Notations and Common Functions p53
  - Monotonicity p53
  - Floors and Ceilings p54
  - Modular Arithmetic p54
  - Polynomials p55
  - Exponentials p55
  - Logarithms p56
  - Factorials p57
  - Functional Iteration p58
  - The iterated logarithm function p58
  - Fibonacci numbers p59

#### 4 Divide and Conquer p65
- Recurrences p65
- Technicalities in recurrences p67
- 4.1 The maximum-subarray problem p68
  - A brute-force solution p69
  - A transformation p69
  - A solution using Divide and Conquer p70
  - Analyzing the divide and conquer algorithm p73
- 4.2 Strassen's algorithm for matrix multiplication p75
  - A simple divide-and-conquer algorithm p76
  - Strassen's method p79
- 4.3 The substitution method for solving recurrences p83
  - Makign a good guess p84
  - Subtleties p85
  - Avoiding pitfalls p86
  - Changing Variables p86
- 4.4 The recursion tree method for solving recurrences p88
  - figure 4.5 Contructing a recursion tree p89
  - figure 4.6 A recursion tree for the recurrence p91
- 4.5 The master method for solving recurrences p93
  - Formula 4.20
  - The master theorem p94
  - Using the master method p95
- 4.6 Proof of the master method p97
  - 4.6.1 Proof for exact powers p98
  - 4.6.2 Floors and Ceilings p103

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
  - rod-cutting problem p360
  - Figure 15.1 A sample price table for rods p360
  - Figure 15.2 The 8 possible ways of cutting up a rod of length 4 p361
  - optimal substructure p362
  - Recursive top-down implementation p363
    - CUT-ROD(p, n) p363
    - Figure 15.3 - The recursion tree showing recursive calls resulting from a call CUT-ROD(p, n) for n = 4 p364
  - Using dynamic programming for optimal rod cutting p364
  - Subproblem graphs p367
  - Reconstructing a solution p368
    - EXTENDED-BOTTOM-UP-CUT-ROD(p, n) 
    - PRINT-CUT-ROD-SOLUTION(p, n) p369
- 15.2 Matrix-chain multiplication p370
  - MATRIX-MULTIPLY(A, B) p371
  - Counting the number of parenthesizations p372
  - Applying dynamic programming p372
  - Step 1: The structure of an optimal parenthesization p373
  - Step 2: A recursive solution p374
  - Step 3: Computing the optimal costs p374
  - Step 4: Constructing an optimal solution p377
- 15.3 Elements of dynamic programming p378
  - Optimal substructure p379
  - Subtleties p381
    - Unweighted shortest path p381
    - Unweighted longest simple path p382
  - Overlapping subproblems p384
  - Reconstructing an optimal solution p387
  - Memoization p387
- 15.4 Longest common subsequence p390
  - Step 1: Characterizing a longest common subsequence p392
  - Step 2: A recursive solution p393
  - Step 3: Computing the length of an LCS p393
  - Step 4: Constructing an LCS p394
  - Improving the code p396
- 15.5 Optimal binary search trees p397
  - Step 1: The structure of an optimal binary search tree p399
  - Step 2: A recursive solution p400
  - Step 3: Computing the expected search cost of an optimal binary search tree p401
    - OPTIMAL-BST(p, q, n) p402
- Chapter notes p412

#### 16 Greedy Algorithms p414
- 16.1 An activity-selection problem p415
  - The optimal substructure of the activity-selection problem p416
  - Making the greedy choice p417
    - Theorem 16.1 p428
    - Proof p418
  - A recursive greedy algorithm p418
    - RECURSIVE-ACTIVITY-SELECTOR(s, f, k, n) p419
  - An iterative greedy algorithm p419
- 16.2 Elements of the greedy strategy p423
  - Greedy-choice property p424
  - Optimal substructure p425
  - Greedy vs dynamic programming p425
- 16.3 Huffman codes p428
  - figure 16.3 - A character coding problem p429
  - Prefix codes p429
    - figure 16.4 Trees corresponding to the coding schemes in Figrue 16.3 
  - Constructing a Huffman code p431
- 16.4 * Matroids and greedy methods p437
  - Matroids p437
    - Theorem 16.5 p438
      - Proof p438
    - Theorem 16.6 
      - Proof p439
    - Greedy algorithms on a weighted matroid p439
      - GREEDY(M, w) p440
    - Lemma 16.7 (Matroids exhibit the greedy-choice property) p441
      - Proof p441
    - Lemma 16.8 p441
      - Proof p441
    - Corollary 16.9 p441
      - Proof p441
    - Lemma 16.10 (Matroids exhibit the optimal-substructure property)
      - Proof p442
    - Theorem 16.11 (Correctness of the greedy algorithm on matroids)
      - Proof p442
- 16.5 * A task-scheduling problem as a matroid p443
  - Lemma 16.12 p445
    - Proof p445
  - Theorem 16.13 
    - Proof p445
    - Figure 16.7 

#### 17 Amortized Analysis p451
- 17.1 Aggregate analysis p452
- 17.2 The accounting method p456
- 17.3 The potential method p459
- 17.4 Dynamic tables p463

## V Advanced Data Structures 
#### 18 B-Trees p484
  - Data structures on secondary storage p484
    - Figure 18.1 B-tree whose keys are the consonants of English p485
    - Figure 18.2 A typical disk drive p485
    - Figure 18.3 A B-tree of height 2 containing over 1 billion keys p488
- 18.1 Definition of B-trees p488
  - The height of a B-tree p489
    - Theorem 18.1 p489
      - Proof p489
- 18.2 Basic operation on B-trees p491
  - Searching a B-tree p491
  - Creating an empty B-tree p492
  - Inserting a key into a B-tree p493
  - Splitting a node in a B-tree p493
  - Inserting a key into a B-tree in a single pass down the tree p495
    - Figure 18.6 Splitting the root with t = 4 p496
    - B-TREE-INSERT-NONFULL(x, k) p496
    - Figure 18.7 Inserting keys into a B-tree p498
- 18.3 Deleting a key from a B-tree p499
  - Figure 18.8 Deleting keys from a B-tree p500
- Problems 
  - 18-1 Stacks on a secondary storage p502
  - 18-2 Joining and splitting 2-3-4 trees p503
- Chapter notes p504

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
  - An application of disjoint-set data structures p562
    - Figure 21.1 (a) A graph with four connected components: {a,b,c,d}, {e,f,g},{h,i} and {j} (b) The collection of disjoint sets after processing each edge p563
    - CONNECTED-COMPONENTS(G) p563
    - SAME-COMPONENT(u, v) p564
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