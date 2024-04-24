# Master the coding interview. Data structures and algorithms
Here is a [mindmap](https://coggle.it/diagram/W5E5tqYlrXvFJPsq/t/master-the-interview-click-here-for-course-link).

## Data structures

### Sequence containers


### Associative containers


### Trees

#### Binary tree
Traits:
1. If all the leaf nodes are full and there is no node that has 1 child, it should
    have either 0 or 2 children - it is called Perfect Binary Tree
    1. The bottom level number of leaves - 1 = sum of all nodes from other levels
        1. lookup, insert, delete operations have complexity(efficiency) of O(logN)

2. Balanced and unbalanced binary tree

3. What are the methods to balance a search tree?

4. When traversing a tree what divide and conquer approach means?

Quiz:
1. So what is the point of learning this BST module if Hash Table can
do the crucial Table ADT operations in unlikely-to-be-beaten expected O(1) time?
- bst deterministic time complexity in a balanced tree
- ordered operations in bst, hash tables not inherently preserve order among elements
- no hash function dependency
- adaptivity
- range queries
2. Why an unbalanced bst is bad?
- this way a part of a tree can become a singly-linked list,
which will have complexity of O(n) for lookup, insert and delete ops.

### Graphs

## Algorithms

### Searching

### Sorting

### BFS and DFS

