
# Tree
## What
A tree is **Graph with no cycles**
    - Nodes : V
    - edges : V - 1

## Why
Tree usages
    - Hierarchical relationships
    - Manage sorted data
    - Enable fast searching operations

## Terms
- Root
- Parent
- Children
- Ancestor
- Descendent
- Siblings
- Leaf
- Depth
    - Height (max Depth)

## Type of trees
- Binary Tree
    - Variations [Different Types of Binary Tree with colourful illustrations](https://towardsdatascience.com/5-types-of-binary-tree-with-cool-illustrations-9b335c430254)
    - Binary Search Tree (BST)
- Ternary Tree
- N-ary Tree


## How do we represent trees?
- 
- 

## Traversal Algorithm
- Depth-First Search (DFS) Algorithm
- Breadth-First Search (BFS) Algorithm


## Tree Traversal
### Achieved by DFS
- Pre-Order
    - 1st time you visit
    - "Root", Left, Right
- In-Order
    - 2nd time you visit
    - Left, "Root",  Right
- Post-Order
    - 3rd time you visit
    - Left,  Right,  "Root"

https://www.youtube.com/watch?v=WLvU5EQVZqY

### Achieved by BSF
- Level-Order

[4 Types of Tree Traversal Algorithms](https://towardsdatascience.com/4-types-of-tree-traversal-algorithms-d56328450846) 

# Analytics
Say if we have a simple request to traverse all Nodes of the tree. The order doesn't matter. What would be the complexity in terms of time and space?

Let's assume the number of all nodes are `n` first.
You can use `h` as a hight of the tree for DFS too.

## DFS
- Time
- Space

## BFS
- Time
- Space


# Exercise1

### dfs
- https://leetcode.com/problems/path-sum/
- https://leetcode.com/problems/binary-tree-inorder-traversal/
- https://leetcode.com/problems/maximum-depth-of-binary-tree/

### bfs
- https://leetcode.com/problems/minimum-depth-of-binary-tree/  
- https://leetcode.com/problems/maximum-depth-of-binary-tree/
- https://leetcode.com/problems/average-of-levels-in-binary-tree/
    
# Exercise2

- https://leetcode.com/problems/same-tree/
- https://leetcode.com/problems/balanced-binary-tree/
- https://leetcode.com/problems/invert-binary-tree/
- https://leetcode.com/problems/search-in-a-binary-search-tree/
    - Try to solve it with `O(h)`: `h` is the hight of the tree

## Advanced🔥
- https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/